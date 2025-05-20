# Function: <code>uart_change_speed</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81502990)
Location: drivers/tty/serial/serial_core.c:443
Inline: True
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_resume_port
```
**Symbols:**

```
ffffffff81502990-ffffffff81502a89: uart_change_speed.isra.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void uart_change_speed(struct tty_struct *tty, struct uart_state *state, struct ktermios *old_termios);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81554020)
Location: drivers/tty/serial/serial_core.c:481
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_startup
```
**Symbols:**

```
ffffffff81554020-ffffffff81554123: uart_change_speed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void uart_change_speed(struct tty_struct *tty, struct uart_state *state, struct ktermios *old_termios);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81580d00)
Location: drivers/tty/serial/serial_core.c:473
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
**Symbols:**

```
ffffffff81580d00-ffffffff81580e03: uart_change_speed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void uart_change_speed(struct tty_struct *tty, struct uart_state *state, struct ktermios *old_termios);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81594c00)
Location: drivers/tty/serial/serial_core.c:474
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
**Symbols:**

```
ffffffff81594c00-ffffffff81594d1a: uart_change_speed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void uart_change_speed(struct tty_struct *tty, struct uart_state *state, struct ktermios *old_termios);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff815f9450)
Location: drivers/tty/serial/serial_core.c:482
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
**Symbols:**

```
ffffffff815f9450-ffffffff815f957c: uart_change_speed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void uart_change_speed(struct tty_struct *tty, struct uart_state *state, struct ktermios *old_termios);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81631f60)
Location: drivers/tty/serial/serial_core.c:489
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
**Symbols:**

```
ffffffff81631f60-ffffffff8163206c: uart_change_speed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void uart_change_speed(struct tty_struct *tty, struct uart_state *state, struct ktermios *old_termios);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff816505d0)
Location: drivers/tty/serial/serial_core.c:502
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_set_info_user
```
**Symbols:**

```
ffffffff816505d0-ffffffff816506dc: uart_change_speed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void uart_change_speed(struct tty_struct *tty, struct uart_state *state, struct ktermios *old_termios);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81685140)
Location: drivers/tty/serial/serial_core.c:499
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_set_info
```
**Symbols:**

```
ffffffff81685140-ffffffff81685257: uart_change_speed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void uart_change_speed(struct tty_struct *tty, struct uart_state *state, struct ktermios *old_termios);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff816a7800)
Location: drivers/tty/serial/serial_core.c:500
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_set_info
```
**Symbols:**

```
ffffffff816a7800-ffffffff816a7917: uart_change_speed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void uart_change_speed(struct tty_struct *tty, struct uart_state *state, struct ktermios *old_termios);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81758850)
Location: drivers/tty/serial/serial_core.c:501
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_port_startup
```
**Symbols:**

```
ffffffff81758850-ffffffff81758967: uart_change_speed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void uart_change_speed(struct tty_struct *tty, struct uart_state *state, struct ktermios *old_termios);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81773910)
Location: drivers/tty/serial/serial_core.c:502
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_port_startup
```
**Symbols:**

```
ffffffff81773910-ffffffff81773a27: uart_change_speed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void uart_change_speed(struct tty_struct *tty, struct uart_state *state, struct ktermios *old_termios);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81758270)
Location: drivers/tty/serial/serial_core.c:502
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_port_startup
```
**Symbols:**

```
ffffffff81758270-ffffffff81758387: uart_change_speed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void uart_change_speed(struct tty_struct *tty, struct uart_state *state, struct ktermios *old_termios);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff817dbb10)
Location: drivers/tty/serial/serial_core.c:485
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_port_startup
```
**Symbols:**

```
ffffffff817dbb10-ffffffff817dbc27: uart_change_speed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void uart_change_speed(struct tty_struct *tty, struct uart_state *state, struct ktermios *old_termios);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81918a60)
Location: drivers/tty/serial/serial_core.c:483
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_port_startup
```
**Symbols:**

```
ffffffff81918a60-ffffffff81918b87: uart_change_speed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void uart_change_speed(struct tty_struct *tty, struct uart_state *state, const struct ktermios *old_termios);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81a74790)
Location: drivers/tty/serial/serial_core.c:489
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_port_startup
```
**Symbols:**

```
ffffffff81a74790-ffffffff81a748b7: uart_change_speed (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void uart_change_speed(struct tty_struct *tty, struct uart_state *state, struct ktermios *old_termios);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffff80001087ea88)
Location: drivers/tty/serial/serial_core.c:500
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_set_info
```
**Symbols:**

```
ffff80001087ea88-ffff80001087ebdc: uart_change_speed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void uart_change_speed(struct tty_struct *tty, struct uart_state *state, struct ktermios *old_termios);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (c097d374)
Location: drivers/tty/serial/serial_core.c:500
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_set_info
```
**Symbols:**

```
c097d374-c097d46c: uart_change_speed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void uart_change_speed(struct tty_struct *tty, struct uart_state *state, struct ktermios *old_termios);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (c000000000926c60)
Location: drivers/tty/serial/serial_core.c:500
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_set_info
```
**Symbols:**

```
c000000000926c60-c000000000926e30: uart_change_speed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void uart_change_speed(struct tty_struct *tty, struct uart_state *state, struct ktermios *old_termios);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffe00054ded8)
Location: drivers/tty/serial/serial_core.c:500
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_port_startup
```
**Symbols:**

```
ffffffe00054ded8-ffffffe00054e00c: uart_change_speed (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void uart_change_speed(struct tty_struct *tty, struct uart_state *state, struct ktermios *old_termios);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8166d260)
Location: drivers/tty/serial/serial_core.c:500
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_set_info
```
**Symbols:**

```
ffffffff8166d260-ffffffff8166d377: uart_change_speed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void uart_change_speed(struct tty_struct *tty, struct uart_state *state, struct ktermios *old_termios);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8164bd20)
Location: drivers/tty/serial/serial_core.c:500
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_set_info
```
**Symbols:**

```
ffffffff8164bd20-ffffffff8164be31: uart_change_speed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void uart_change_speed(struct tty_struct *tty, struct uart_state *state, struct ktermios *old_termios);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8169b640)
Location: drivers/tty/serial/serial_core.c:500
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_set_info
```
**Symbols:**

```
ffffffff8169b640-ffffffff8169b757: uart_change_speed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void uart_change_speed(struct tty_struct *tty, struct uart_state *state, struct ktermios *old_termios);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff816b3d80)
Location: drivers/tty/serial/serial_core.c:500
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_set_info
```
**Symbols:**

```
ffffffff816b3d80-ffffffff816b3e8e: uart_change_speed (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct ktermios *old_termios</code> ➡️ <code>const struct ktermios *old_termios</code>
</li>
</ul>
</details>
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
