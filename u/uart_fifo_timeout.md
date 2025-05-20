# Function: <code>uart_fifo_timeout</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81a76a79)
Location: include/linux/serial_core.h:760
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff81a7adbf)
Location: include/linux/serial_core.h:760
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_timer
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_timer
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_timeout
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
In drivers/tty/serial/serial_core.c (ffffffff81ac1519)
Location: include/linux/serial_core.h:765
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff81ac662f)
Location: include/linux/serial_core.h:765
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_timer
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_timer
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_timeout
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
In drivers/tty/serial/serial_core.c (ffffffff81b14359)
Location: include/linux/serial_core.h:866
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff81b1965f)
Location: include/linux/serial_core.h:866
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_timer
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_timer
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_timeout
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
