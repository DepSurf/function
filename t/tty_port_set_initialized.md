# Function: <code>tty_port_set_initialized</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff8153c90e)
Location: include/linux/tty.h:620
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/serial/serial_core.c (ffffffff81555243)
Location: include/linux/tty.h:620
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_startup
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
In drivers/tty/tty_port.c (ffffffff81568f5e)
Location: include/linux/tty.h:620
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/serial/serial_core.c (ffffffff81581f07)
Location: include/linux/tty.h:620
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_shutdown
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
In drivers/tty/tty_port.c (ffffffff8157c64e)
Location: include/linux/tty.h:647
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/serial/serial_core.c (ffffffff81596336)
Location: include/linux/tty.h:647
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_shutdown
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
In drivers/tty/tty_port.c (ffffffff815e1091)
Location: include/linux/tty.h:653
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/serial/serial_core.c (ffffffff815faf2a)
Location: include/linux/tty.h:653
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_shutdown
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
In drivers/tty/tty_port.c (ffffffff8161a321)
Location: include/linux/tty.h:655
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/serial/serial_core.c (ffffffff8163305e)
Location: include/linux/tty.h:655
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_shutdown
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
In drivers/tty/tty_port.c (ffffffff816375a1)
Location: include/linux/tty.h:663
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/serial/serial_core.c (ffffffff8165215e)
Location: include/linux/tty.h:663
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_set_info_user
  - drivers/tty/serial/serial_core.c:uart_set_info_user
  - drivers/tty/serial/serial_core.c:uart_shutdown
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
In drivers/tty/tty_port.c (ffffffff8166b827)
Location: include/linux/tty.h:663
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/serial/serial_core.c (ffffffff81686c76)
Location: include/linux/tty.h:663
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_shutdown
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
In drivers/tty/tty_port.c (ffffffff8168dec7)
Location: include/linux/tty.h:665
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/serial/serial_core.c (ffffffff816a9386)
Location: include/linux/tty.h:665
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_shutdown
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
In drivers/tty/tty_port.c (ffffffff817401e7)
Location: include/linux/tty.h:665
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8175475b)
Location: include/linux/tty.h:665
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_close
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_open
```
```
In drivers/tty/serial/serial_core.c (ffffffff8175b5c6)
Location: include/linux/tty.h:665
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_do_autoconfig
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_shutdown
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
In drivers/tty/tty_port.c (ffffffff8175c117)
Location: include/linux/tty.h:657
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8176f9cb)
Location: include/linux/tty.h:657
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_close
  - drivers/tty/hvc/hvc_console.c:hvc_open
```
```
In drivers/tty/serial/serial_core.c (ffffffff817766a6)
Location: include/linux/tty.h:657
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_do_autoconfig
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_shutdown
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
In drivers/tty/tty_port.c (ffffffff8173ffb7)
Location: include/linux/tty.h:588
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff817534ab)
Location: include/linux/tty.h:588
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_close
  - drivers/tty/hvc/hvc_console.c:hvc_open
```
```
In drivers/tty/serial/serial_core.c (ffffffff8175a286)
Location: include/linux/tty.h:588
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_shutdown
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
In drivers/tty/tty_port.c (ffffffff817c0757)
Location: include/linux/tty_port.h:168
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff817d689b)
Location: include/linux/tty_port.h:168
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_close
  - drivers/tty/hvc/hvc_console.c:hvc_open
```
```
In drivers/tty/serial/serial_core.c (ffffffff817dd7d5)
Location: include/linux/tty_port.h:168
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_shutdown
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
In drivers/tty/tty_port.c (ffffffff818fcf79)
Location: include/linux/tty_port.h:214
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8191495f)
Location: include/linux/tty_port.h:214
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_close
  - drivers/tty/hvc/hvc_console.c:hvc_open
```
```
In drivers/tty/serial/serial_core.c (ffffffff8191c1ca)
Location: include/linux/tty_port.h:214
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_shutdown
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
In drivers/tty/tty_port.c (ffffffff81a56659)
Location: include/linux/tty_port.h:216
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81a6fa2f)
Location: include/linux/tty_port.h:216
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_close
  - drivers/tty/hvc/hvc_console.c:hvc_open
```
```
In drivers/tty/serial/serial_core.c (ffffffff81a78136)
Location: include/linux/tty_port.h:216
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_shutdown
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
In drivers/tty/tty_port.c (ffffffff81aa0c39)
Location: include/linux/tty_port.h:216
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81aba1df)
Location: include/linux/tty_port.h:216
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_close
  - drivers/tty/hvc/hvc_console.c:hvc_open
```
```
In drivers/tty/serial/serial_core.c (ffffffff81ac2be6)
Location: include/linux/tty_port.h:216
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_shutdown
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
In drivers/tty/tty_port.c (ffffffff81af3699)
Location: include/linux/tty_port.h:217
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81b0cf0f)
Location: include/linux/tty_port.h:217
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_close
  - drivers/tty/hvc/hvc_console.c:hvc_open
```
```
In drivers/tty/serial/serial_core.c (ffffffff81b14bba)
Location: include/linux/tty_port.h:217
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_shutdown
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
In drivers/tty/tty_port.c (ffff80001085ef30)
Location: include/linux/tty.h:665
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/serial/serial_core.c (ffff800010880fa0)
Location: include/linux/tty.h:665
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_shutdown
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
In drivers/tty/tty_port.c (c096622c)
Location: include/linux/tty.h:665
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/serial/serial_core.c (c0981164)
Location: include/linux/tty.h:665
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_shutdown
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
In drivers/tty/tty_port.c (c0000000008fe5dc)
Location: include/linux/tty.h:665
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/serial/serial_core.c (c00000000092a19c)
Location: include/linux/tty.h:665
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_shutdown
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
In drivers/tty/tty_port.c (ffffffe0005372f6)
Location: include/linux/tty.h:665
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/serial/serial_core.c (ffffffe00054f5c0)
Location: include/linux/tty.h:665
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_shutdown
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
In drivers/tty/tty_port.c (ffffffff81653947)
Location: include/linux/tty.h:665
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/serial/serial_core.c (ffffffff8166ede6)
Location: include/linux/tty.h:665
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_shutdown
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
In drivers/tty/tty_port.c (ffffffff81633d31)
Location: include/linux/tty.h:665
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/serial/serial_core.c (ffffffff8164ddea)
Location: include/linux/tty.h:665
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_shutdown
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
In drivers/tty/tty_port.c (ffffffff81681d07)
Location: include/linux/tty.h:665
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/serial/serial_core.c (ffffffff8169d1c6)
Location: include/linux/tty.h:665
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_shutdown
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
In drivers/tty/tty_port.c (ffffffff8169c34e)
Location: include/linux/tty.h:665
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/serial/serial_core.c (ffffffff816b6154)
Location: include/linux/tty.h:665
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
</details>
</li>
</ul>

## Differences
