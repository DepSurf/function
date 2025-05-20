# Function: <code>tty_vhangup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void tty_vhangup(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff814e1720)
Location: drivers/tty/tty_io.c:799
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_vhangup_self
  - drivers/tty/tty_io.c:tty_ioctl
Direct callers:
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
ffffffff814e1720-ffffffff814e1732: tty_vhangup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void tty_vhangup(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81534569)
Location: drivers/tty/tty_io.c:805
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_vhangup_self
Direct callers:
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
ffffffff81532b50-ffffffff81532b62: tty_vhangup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void tty_vhangup(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81560c94)
Location: drivers/tty/tty_io.c:805
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_vhangup_self
Direct callers:
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
ffffffff8155f280-ffffffff8155f292: tty_vhangup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void tty_vhangup(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81573e7a)
Location: drivers/tty/tty_io.c:670
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_vhangup_self
Direct callers:
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
ffffffff81573980-ffffffff81573999: tty_vhangup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void tty_vhangup(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815d836a)
Location: drivers/tty/tty_io.c:682
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_vhangup_self
Direct callers:
  - drivers/tty/pty.c:pty_close
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
ffffffff815d7e50-ffffffff815d7e69: tty_vhangup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void tty_vhangup(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81611cef)
Location: drivers/tty/tty_io.c:691
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_vhangup_self
Direct callers:
  - drivers/tty/pty.c:pty_close
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
ffffffff81611280-ffffffff81611298: tty_vhangup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void tty_vhangup(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8162ea64)
Location: drivers/tty/tty_io.c:692
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_vhangup_self
Direct callers:
  - drivers/tty/pty.c:pty_close
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
ffffffff8162de20-ffffffff8162de38: tty_vhangup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void tty_vhangup(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8166286f)
Location: drivers/tty/tty_io.c:694
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_vhangup_self
Direct callers:
  - drivers/tty/pty.c:pty_close
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
ffffffff816619f0-ffffffff81661a08: tty_vhangup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void tty_vhangup(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81684edf)
Location: drivers/tty/tty_io.c:694
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_vhangup_self
Direct callers:
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
ffffffff81684040-ffffffff81684058: tty_vhangup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void tty_vhangup(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81736549)
Location: drivers/tty/tty_io.c:695
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_vhangup_self
Direct callers:
  - drivers/tty/pty.c:pty_close
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
ffffffff81735d80-ffffffff81735d98: tty_vhangup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void tty_vhangup(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81752f4c)
Location: drivers/tty/tty_io.c:693
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_vhangup_self
Direct callers:
  - drivers/tty/pty.c:pty_close
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
ffffffff81752320-ffffffff81752338: tty_vhangup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void tty_vhangup(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81736f3b)
Location: drivers/tty/tty_io.c:709
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_vhangup_self
Direct callers:
  - drivers/tty/pty.c:pty_close
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
ffffffff81736470-ffffffff81736488: tty_vhangup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void tty_vhangup(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817b7914)
Location: drivers/tty/tty_io.c:708
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_vhangup_self
Direct callers:
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
ffffffff817b6e30-ffffffff817b6e48: tty_vhangup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void tty_vhangup(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff818f2d8c)
Location: drivers/tty/tty_io.c:704
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_vhangup_self
  - drivers/tty/tty_io.c:tty_vhangup_self
Direct callers:
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
ffffffff818f24c0-ffffffff818f24e8: tty_vhangup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void tty_vhangup(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a4b3d0)
Location: drivers/tty/tty_io.c:698
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_vhangup_self
  - drivers/tty/tty_io.c:tty_vhangup_self
Direct callers:
  - drivers/tty/pty.c:pty_close
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
ffffffff81a4aa50-ffffffff81a4aa78: tty_vhangup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void tty_vhangup(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a95502)
Location: drivers/tty/tty_io.c:699
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_vhangup_self
  - drivers/tty/tty_io.c:tty_vhangup_self
Direct callers:
  - drivers/tty/pty.c:pty_close
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/serial_core.c:serial_core_remove_one_port
```
**Symbols:**

```
ffffffff81a94c60-ffffffff81a94c88: tty_vhangup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void tty_vhangup(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81ae7ee0)
Location: drivers/tty/tty_io.c:697
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_vhangup_self
  - drivers/tty/tty_io.c:tty_vhangup_self
Direct callers:
  - drivers/tty/pty.c:pty_close
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/serial_core.c:serial_core_remove_one_port
```
**Symbols:**

```
ffffffff81ae8110-ffffffff81ae8138: tty_vhangup (STB_GLOBAL)
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
void tty_vhangup(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffff800010852294)
Location: drivers/tty/tty_io.c:694
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_vhangup_self
Direct callers:
  - drivers/tty/pty.c:pty_close
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
ffff800010851688-ffff8000108516bc: tty_vhangup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void tty_vhangup(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c095cf44)
Location: drivers/tty/tty_io.c:694
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_vhangup_self
Direct callers:
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
c095c0fc-c095c124: tty_vhangup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void tty_vhangup(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c0000000008f0f5c)
Location: drivers/tty/tty_io.c:694
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_vhangup_self
Direct callers:
  - drivers/tty/pty.c:pty_close
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
c0000000008f03a0-c0000000008f03c0: tty_vhangup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void tty_vhangup(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffe00052f5d6)
Location: drivers/tty/tty_io.c:694
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_vhangup_self
Direct callers:
  - drivers/tty/pty.c:pty_close
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
ffffffe00052ecdc-ffffffe00052ed0a: tty_vhangup (STB_GLOBAL)
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
void tty_vhangup(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8164a95f)
Location: drivers/tty/tty_io.c:694
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_vhangup_self
Direct callers:
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
ffffffff81649ac0-ffffffff81649ad8: tty_vhangup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void tty_vhangup(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8162adaf)
Location: drivers/tty/tty_io.c:694
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_vhangup_self
Direct callers:
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
ffffffff81629f10-ffffffff81629f28: tty_vhangup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void tty_vhangup(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81678d1f)
Location: drivers/tty/tty_io.c:694
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_vhangup_self
Direct callers:
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
ffffffff81677e80-ffffffff81677e98: tty_vhangup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void tty_vhangup(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8169295a)
Location: drivers/tty/tty_io.c:694
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_vhangup_self
Direct callers:
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
ffffffff81692290-ffffffff816922a8: tty_vhangup (STB_GLOBAL)
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
