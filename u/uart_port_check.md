# Function: <code>uart_port_check</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: drivers/tty/serial/serial_core.c:96
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: drivers/tty/serial/serial_core.c:97
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: drivers/tty/serial/serial_core.c:98
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: drivers/tty/serial/serial_core.c:85
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: drivers/tty/serial/serial_core.c:85
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: drivers/tty/serial/serial_core.c:85
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: drivers/tty/serial/serial_core.c:85
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: drivers/tty/serial/serial_core.c:86
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff817578c1)
Location: drivers/tty/serial/serial_core.c:87
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/serial_core.c:console_store
  - drivers/tty/serial/serial_core.c:console_show
  - drivers/tty/serial/serial_core.c:uart_poll_init
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_hangup
  - drivers/tty/serial/serial_core.c:uart_hangup
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_set_ldisc
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_do_autoconfig
  - drivers/tty/serial/serial_core.c:uart_break_ctl
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_tiocmget
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/tty/serial/serial_core.c:uart_change_speed
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_port_startup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81772981)
Location: drivers/tty/serial/serial_core.c:88
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/serial_core.c:console_store
  - drivers/tty/serial/serial_core.c:console_show
  - drivers/tty/serial/serial_core.c:uart_poll_init
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_hangup
  - drivers/tty/serial/serial_core.c:uart_hangup
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_set_ldisc
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_do_autoconfig
  - drivers/tty/serial/serial_core.c:uart_break_ctl
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_tiocmget
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/tty/serial/serial_core.c:uart_change_speed
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_port_startup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff817563fc)
Location: drivers/tty/serial/serial_core.c:88
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/serial_core.c:console_store
  - drivers/tty/serial/serial_core.c:console_show
  - drivers/tty/serial/serial_core.c:uart_poll_init
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_hangup
  - drivers/tty/serial/serial_core.c:uart_hangup
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_set_ldisc
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_break_ctl
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_tiocmget
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/tty/serial/serial_core.c:uart_change_speed
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_port_startup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff817d9b2c)
Location: drivers/tty/serial/serial_core.c:88
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_core.c:console_store
  - drivers/tty/serial/serial_core.c:console_show
  - drivers/tty/serial/serial_core.c:uart_poll_init
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_hangup
  - drivers/tty/serial/serial_core.c:uart_hangup
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_set_ldisc
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_break_ctl
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_tiocmget
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/tty/serial/serial_core.c:uart_change_speed
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_port_startup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81918557)
Location: drivers/tty/serial/serial_core.c:94
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_core.c:console_store
  - drivers/tty/serial/serial_core.c:console_show
  - drivers/tty/serial/serial_core.c:uart_poll_init
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_hangup
  - drivers/tty/serial/serial_core.c:uart_hangup
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_set_ldisc
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_break_ctl
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_tiocmget
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/tty/serial/serial_core.c:uart_change_speed
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_port_startup
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81a73f77)
Location: drivers/tty/serial/serial_core.c:94
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_core.c:console_store
  - drivers/tty/serial/serial_core.c:console_show
  - drivers/tty/serial/serial_core.c:uart_poll_init
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_port_activate
  - drivers/tty/serial/serial_core.c:uart_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_hangup
  - drivers/tty/serial/serial_core.c:uart_hangup
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_set_ldisc
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_break_ctl
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_tiocmget
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/tty/serial/serial_core.c:uart_change_speed
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_port_startup
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81abe5fb)
Location: drivers/tty/serial/serial_core.c:95
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:serial_core_remove_one_port
  - drivers/tty/serial/serial_core.c:serial_core_add_one_port
  - drivers/tty/serial/serial_core.c:serial_core_add_one_port
  - drivers/tty/serial/serial_core.c:console_store
  - drivers/tty/serial/serial_core.c:console_show
  - drivers/tty/serial/serial_core.c:uart_poll_init
  - drivers/tty/serial/serial_core.c:uart_poll_init
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_port_activate
  - drivers/tty/serial/serial_core.c:uart_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_hangup
  - drivers/tty/serial/serial_core.c:uart_hangup
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_set_ldisc
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_break_ctl
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_tiocmget
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/tty/serial/serial_core.c:uart_change_line_settings
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81b1137b)
Location: drivers/tty/serial/serial_core.c:95
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:serial_core_remove_one_port
  - drivers/tty/serial/serial_core.c:serial_core_add_one_port
  - drivers/tty/serial/serial_core.c:serial_core_add_one_port
  - drivers/tty/serial/serial_core.c:console_store
  - drivers/tty/serial/serial_core.c:console_show
  - drivers/tty/serial/serial_core.c:uart_poll_init
  - drivers/tty/serial/serial_core.c:uart_poll_init
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_port_activate
  - drivers/tty/serial/serial_core.c:uart_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_hangup
  - drivers/tty/serial/serial_core.c:uart_hangup
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_set_ldisc
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_break_ctl
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_tiocmget
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/tty/serial/serial_core.c:uart_change_line_settings
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: drivers/tty/serial/serial_core.c:86
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (c097f1ac)
Location: drivers/tty/serial/serial_core.c:86
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_core.c:uart_poll_init
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_line_info
  - drivers/tty/serial/serial_core.c:uart_line_info
  - drivers/tty/serial/serial_core.c:uart_line_info
  - drivers/tty/serial/serial_core.c:uart_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_hangup
  - drivers/tty/serial/serial_core.c:uart_hangup
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_set_ldisc
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_break_ctl
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_tiocmget
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/tty/serial/serial_core.c:uart_change_speed
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (c000000000924470)
Location: drivers/tty/serial/serial_core.c:86
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_core.c:uart_poll_init
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_hangup
  - drivers/tty/serial/serial_core.c:uart_hangup
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_set_ldisc
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_break_ctl
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_tiocmget
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/tty/serial/serial_core.c:uart_change_speed
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffe00054c088)
Location: drivers/tty/serial/serial_core.c:86
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_hangup
  - drivers/tty/serial/serial_core.c:uart_hangup
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_set_ldisc
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_break_ctl
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_tiocmget
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/tty/serial/serial_core.c:uart_change_speed
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_port_startup
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: drivers/tty/serial/serial_core.c:86
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: drivers/tty/serial/serial_core.c:86
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: drivers/tty/serial/serial_core.c:86
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: drivers/tty/serial/serial_core.c:86
Inline: True
```
</details>
</li>
</ul>

## Differences
