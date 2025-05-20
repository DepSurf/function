# Function: <code>serdev_controller_get_drvdata</code>

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
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff8160a4b3)
Location: include/linux/serdev.h:141
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_unregister
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_tiocm
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_get_tiocm
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_wait_until_sent
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_flush
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_buf
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_receive_buf
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
In drivers/tty/serdev/serdev-ttyport.c (ffffffff81643df8)
Location: include/linux/serdev.h:150
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_unregister
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_tiocm
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_get_tiocm
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_wait_until_sent
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_flush
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_buf
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_receive_buf
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
In drivers/tty/serdev/serdev-ttyport.c (ffffffff816620c8)
Location: include/linux/serdev.h:150
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_unregister
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_tiocm
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_get_tiocm
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_wait_until_sent
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_flush
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_buf
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_receive_buf
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
In drivers/tty/serdev/serdev-ttyport.c (ffffffff81697c53)
Location: include/linux/serdev.h:142
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_unregister
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_tiocm
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_get_tiocm
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_wait_until_sent
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_flush
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_buf
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_receive_buf
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
In drivers/tty/serdev/serdev-ttyport.c (ffffffff816ba7d3)
Location: include/linux/serdev.h:142
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_unregister
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_tiocm
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_get_tiocm
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_wait_until_sent
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_flush
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_buf
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_receive_buf
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
In drivers/tty/serdev/serdev-ttyport.c (ffffffff8176ec43)
Location: include/linux/serdev.h:142
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_unregister
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_tiocm
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_get_tiocm
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_wait_until_sent
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_flush
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_buf
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_receive_buf
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
In drivers/tty/serdev/serdev-ttyport.c (ffffffff81789543)
Location: include/linux/serdev.h:142
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_unregister
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_tiocm
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_get_tiocm
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_wait_until_sent
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_flush
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_buf
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_receive_buf
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
In drivers/tty/serdev/serdev-ttyport.c (ffffffff8176ce23)
Location: include/linux/serdev.h:142
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_unregister
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_tiocm
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_get_tiocm
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_wait_until_sent
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_flush
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_buf
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_receive_buf
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
In drivers/tty/serdev/serdev-ttyport.c (ffffffff817f2563)
Location: include/linux/serdev.h:142
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_unregister
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_tiocm
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_get_tiocm
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_wait_until_sent
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_flush
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_buf
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_receive_buf
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
In drivers/tty/serdev/serdev-ttyport.c (ffffffff81932dd3)
Location: include/linux/serdev.h:142
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_unregister
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_tiocm
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_get_tiocm
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_wait_until_sent
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_flush
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_buf
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_receive_buf
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
In drivers/tty/serdev/serdev-ttyport.c (ffffffff81a91a23)
Location: include/linux/serdev.h:144
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_unregister
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_tiocm
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_get_tiocm
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_wait_until_sent
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_flush
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_buf
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_receive_buf
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
In drivers/tty/serdev/serdev-ttyport.c (ffffffff81add293)
Location: include/linux/serdev.h:145
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_unregister
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_break_ctl
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_tiocm
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_get_tiocm
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_wait_until_sent
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_flush
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_buf
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_receive_buf
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
In drivers/tty/serdev/serdev-ttyport.c (ffffffff81b306a3)
Location: include/linux/serdev.h:147
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_unregister
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_break_ctl
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_tiocm
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_get_tiocm
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_wait_until_sent
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_flush
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_buf
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_receive_buf
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
In drivers/tty/serdev/serdev-ttyport.c (ffff8000108aaa2c)
Location: include/linux/serdev.h:142
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_unregister
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_tiocm
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_get_tiocm
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_wait_until_sent
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_flush
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_buf
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_receive_buf
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
In drivers/tty/serdev/serdev-ttyport.c (c09a6d6c)
Location: include/linux/serdev.h:142
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_unregister
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_tiocm
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_get_tiocm
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_wait_until_sent
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_flush
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_buf
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_receive_buf
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
In drivers/tty/serdev/serdev-ttyport.c (c0000000009421cc)
Location: include/linux/serdev.h:142
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_unregister
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_tiocm
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_get_tiocm
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_wait_until_sent
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_flush
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_buf
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_receive_buf
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
In drivers/tty/serdev/serdev-ttyport.c (ffffffe00055fa5e)
Location: include/linux/serdev.h:142
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_unregister
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_tiocm
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_get_tiocm
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_wait_until_sent
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_flush
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_buf
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_receive_buf
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
In drivers/tty/serdev/serdev-ttyport.c (ffffffff81680233)
Location: include/linux/serdev.h:142
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_unregister
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_tiocm
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_get_tiocm
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_wait_until_sent
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_flush
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_buf
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_receive_buf
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff816ae613)
Location: include/linux/serdev.h:142
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_unregister
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_tiocm
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_get_tiocm
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_wait_until_sent
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_flush
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_buf
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_receive_buf
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
In drivers/tty/serdev/serdev-ttyport.c (ffffffff816c8a73)
Location: include/linux/serdev.h:142
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_unregister
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_tiocm
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_get_tiocm
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_wait_until_sent
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_flush
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_buf
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_receive_buf
```
</details>
</li>
</ul>

## Differences
