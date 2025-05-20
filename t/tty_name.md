# Function: <code>tty_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
const char *tty_name(const struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff814df530)
Location: drivers/tty/tty_io.c:250
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__proc_set_tty
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
**Symbols:**

```
ffffffff814df530-ffffffff814df550: tty_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
const char *tty_name(const struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8153497b)
Location: drivers/tty/tty_io.c:243
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:__proc_set_tty
  - drivers/tty/tty_io.c:check_tty_count
Direct callers:
  - kernel/auditsc.c:audit_set_loginuid
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
**Symbols:**

```
ffffffff815305f0-ffffffff81530610: tty_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
const char *tty_name(const struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815610ab)
Location: drivers/tty/tty_io.c:243
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:__proc_set_tty
  - drivers/tty/tty_io.c:check_tty_count
Direct callers:
  - kernel/auditsc.c:audit_set_loginuid
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
**Symbols:**

```
ffffffff8155cd40-ffffffff8155cd60: tty_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
const char *tty_name(const struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81573507)
Location: drivers/tty/tty_io.c:244
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:check_tty_count
Direct callers:
  - kernel/auditsc.c:audit_set_loginuid
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
**Symbols:**

```
ffffffff81571790-ffffffff815717b0: tty_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
const char *tty_name(const struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815d8f8a)
Location: drivers/tty/tty_io.c:245
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:check_tty_count
Direct callers:
  - kernel/auditsc.c:audit_set_loginuid
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
**Symbols:**

```
ffffffff815d5cb0-ffffffff815d5cd0: tty_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
const char *tty_name(const struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff816117c8)
Location: drivers/tty/tty_io.c:245
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:check_tty_count
Direct callers:
  - kernel/auditsc.c:audit_set_loginuid
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
**Symbols:**

```
ffffffff8160edc0-ffffffff8160ede0: tty_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
const char *tty_name(const struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8162e538)
Location: drivers/tty/tty_io.c:246
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:check_tty_count
Direct callers:
  - kernel/auditsc.c:audit_set_loginuid
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/serial/serial_core.c:uart_set_info_user
```
**Symbols:**

```
ffffffff8162b9a0-ffffffff8162b9c0: tty_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
const char *tty_name(const struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8166210c)
Location: drivers/tty/tty_io.c:246
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:check_tty_count
Direct callers:
  - kernel/audit.c:audit_set_loginuid
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/serial/serial_core.c:uart_set_info
```
**Symbols:**

```
ffffffff8165f8d0-ffffffff8165f8f0: tty_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
const char *tty_name(const struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8168477c)
Location: drivers/tty/tty_io.c:246
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:check_tty_count
Direct callers:
  - kernel/audit.c:audit_set_loginuid
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/serial/serial_core.c:uart_set_info
```
**Symbols:**

```
ffffffff81681f10-ffffffff81681f30: tty_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
const char *tty_name(const struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81738697)
Location: drivers/tty/tty_io.c:247
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release_checks
  - drivers/tty/tty_io.c:tty_release_checks
  - drivers/tty/tty_io.c:tty_release_checks
  - drivers/tty/tty_io.c:tty_release_checks
  - drivers/tty/tty_io.c:tty_write
Direct callers:
  - kernel/audit.c:audit_log_set_loginuid
  - kernel/audit.c:audit_log_multicast
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/serial/serial_core.c:uart_set_info
```
**Symbols:**

```
ffffffff817333a0-ffffffff817333c0: tty_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
const char *tty_name(const struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81c0755f)
Location: drivers/tty/tty_io.c:244
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release_checks
  - drivers/tty/tty_io.c:tty_release_checks
  - drivers/tty/tty_io.c:tty_release_checks
  - drivers/tty/tty_io.c:tty_release_checks
Direct callers:
  - kernel/audit.c:audit_log_set_loginuid
  - kernel/audit.c:audit_log_multicast
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/serial/serial_core.c:uart_set_info
```
**Symbols:**

```
ffffffff8174f500-ffffffff8174f520: tty_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
const char *tty_name(const struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81bf921f)
Location: drivers/tty/tty_io.c:245
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release_checks
  - drivers/tty/tty_io.c:tty_release_checks
  - drivers/tty/tty_io.c:tty_release_checks
  - drivers/tty/tty_io.c:tty_release_checks
Direct callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_multicast
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/serial/serial_core.c:uart_set_info
```
**Symbols:**

```
ffffffff817334b0-ffffffff817334d0: tty_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
const char *tty_name(const struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81cf89bc)
Location: drivers/tty/tty_io.c:245
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release_checks
  - drivers/tty/tty_io.c:tty_release_checks
  - drivers/tty/tty_io.c:tty_release_checks
  - drivers/tty/tty_io.c:tty_release_checks
Direct callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_multicast
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/serial/serial_core.c:uart_set_info
```
**Symbols:**

```
ffffffff817b3e40-ffffffff817b3e60: tty_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
const char *tty_name(const struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81ec0b1e)
Location: drivers/tty/tty_io.c:244
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release_checks
  - drivers/tty/tty_io.c:tty_release_checks
  - drivers/tty/tty_io.c:tty_release_checks
  - drivers/tty/tty_io.c:tty_release_checks
Direct callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_multicast
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_port.c:tty_port_close_start
  - drivers/tty/tty_port.c:tty_port_close_start
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/serial/serial_core.c:uart_set_info
```
**Symbols:**

```
ffffffff818efa30-ffffffff818efa58: tty_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
const char *tty_name(const struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a4c838)
Location: drivers/tty/tty_io.c:243
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release_checks
  - drivers/tty/tty_io.c:tty_release_checks
  - drivers/tty/tty_io.c:tty_release_checks
  - drivers/tty/tty_io.c:tty_release_checks
Direct callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_multicast
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_port.c:tty_port_close_start
  - drivers/tty/tty_port.c:tty_port_close_start
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/serial/serial_core.c:uart_set_info
```
**Symbols:**

```
ffffffff81a47a70-ffffffff81a47a98: tty_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
const char *tty_name(const struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a96b28)
Location: drivers/tty/tty_io.c:244
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release_checks
  - drivers/tty/tty_io.c:tty_release_checks
  - drivers/tty/tty_io.c:tty_release_checks
  - drivers/tty/tty_io.c:tty_release_checks
Direct callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_multicast
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_port.c:tty_port_close_start
  - drivers/tty/tty_port.c:tty_port_close_start
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/serial/serial_core.c:uart_set_info
```
**Symbols:**

```
ffffffff81a91c10-ffffffff81a91c38: tty_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
const char *tty_name(const struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81ae9518)
Location: drivers/tty/tty_io.c:244
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release_checks
  - drivers/tty/tty_io.c:tty_release_checks
  - drivers/tty/tty_io.c:tty_release_checks
  - drivers/tty/tty_io.c:tty_release_checks
  - drivers/tty/tty_io.c:check_tty_count
Direct callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_multicast
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_port.c:tty_port_close_start
  - drivers/tty/tty_port.c:tty_port_close_start
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/serial/serial_core.c:uart_set_info
```
**Symbols:**

```
ffffffff81ae45a0-ffffffff81ae45c8: tty_name (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
const char *tty_name(const struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffff800010851c3c)
Location: drivers/tty/tty_io.c:246
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:check_tty_count
Direct callers:
  - kernel/audit.c:audit_set_loginuid
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/serial/serial_core.c:uart_set_info
```
**Symbols:**

```
ffff80001084e1c0-ffff80001084e1f8: tty_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
const char *tty_name(const struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c095c7b0)
Location: drivers/tty/tty_io.c:246
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:check_tty_count
Direct callers:
  - kernel/audit.c:audit_set_loginuid
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/serial/serial_core.c:uart_set_info
```
**Symbols:**

```
c095a198-c095a1c0: tty_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
const char *tty_name(const struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c0000000008ef580)
Location: drivers/tty/tty_io.c:246
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:check_tty_count
Direct callers:
  - kernel/audit.c:audit_set_loginuid
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/serial/serial_core.c:uart_set_info
```
**Symbols:**

```
c0000000008ec8d0-c0000000008ec8fc: tty_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
const char *tty_name(const struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffe00052f164)
Location: drivers/tty/tty_io.c:246
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:check_tty_count
Direct callers:
  - kernel/audit.c:audit_set_loginuid
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/serial/serial_core.c:uart_set_info
```
**Symbols:**

```
ffffffe00052c8a6-ffffffe00052c8de: tty_name (STB_GLOBAL)
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
const char *tty_name(const struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8164a1fc)
Location: drivers/tty/tty_io.c:246
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:check_tty_count
Direct callers:
  - kernel/audit.c:audit_set_loginuid
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/serial/serial_core.c:uart_set_info
```
**Symbols:**

```
ffffffff81647990-ffffffff816479b0: tty_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
const char *tty_name(const struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8162a64c)
Location: drivers/tty/tty_io.c:246
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:check_tty_count
Direct callers:
  - kernel/audit.c:audit_set_loginuid
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/serial/serial_core.c:uart_set_info
```
**Symbols:**

```
ffffffff81627df0-ffffffff81627e10: tty_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
const char *tty_name(const struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff816785bc)
Location: drivers/tty/tty_io.c:246
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:check_tty_count
Direct callers:
  - kernel/audit.c:audit_set_loginuid
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/serial/serial_core.c:uart_set_info
```
**Symbols:**

```
ffffffff81675d50-ffffffff81675d70: tty_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
const char *tty_name(const struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81693774)
Location: drivers/tty/tty_io.c:246
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:check_tty_count
Direct callers:
  - kernel/audit.c:audit_set_loginuid
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/serial/serial_core.c:uart_set_info
```
**Symbols:**

```
ffffffff816903b0-ffffffff816903d0: tty_name (STB_GLOBAL)
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
