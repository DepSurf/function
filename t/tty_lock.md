# Function: <code>tty_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void tty_lock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_mutex.c (ffffffff818243a0)
Location: drivers/tty/tty_mutex.c:13
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:__tty_hangup
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_write_message
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_mutex.c:tty_lock_slave
```
**Symbols:**

```
ffffffff818243a0-ffffffff81824420: tty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tty_lock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_mutex.c (ffffffff8153cab0)
Location: drivers/tty/tty_mutex.c:13
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write_message
  - drivers/tty/tty_io.c:__tty_hangup
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_mutex.c:tty_lock_slave
```
**Symbols:**

```
ffffffff8153cab0-ffffffff8153cb32: tty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tty_lock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_mutex.c (ffffffff81569100)
Location: drivers/tty/tty_mutex.c:13
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write_message
  - drivers/tty/tty_io.c:__tty_hangup
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_mutex.c:tty_lock_slave
```
**Symbols:**

```
ffffffff81569100-ffffffff81569182: tty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tty_lock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_mutex.c (ffffffff8157c6a0)
Location: drivers/tty/tty_mutex.c:13
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write_message
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_mutex.c:tty_lock_slave
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff8157c6a0-ffffffff8157c6d8: tty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tty_lock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_mutex.c (ffffffff815e11e0)
Location: drivers/tty/tty_mutex.c:14
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write_message
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_mutex.c:tty_lock_slave
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
```
**Symbols:**

```
ffffffff815e11e0-ffffffff815e121e: tty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tty_lock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_mutex.c (ffffffff8161a470)
Location: drivers/tty/tty_mutex.c:14
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write_message
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_mutex.c:tty_lock_slave
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
```
**Symbols:**

```
ffffffff8161a470-ffffffff8161a4ae: tty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tty_lock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_mutex.c (ffffffff816376f0)
Location: drivers/tty/tty_mutex.c:14
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write_message
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_mutex.c:tty_lock_slave
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
```
**Symbols:**

```
ffffffff816376f0-ffffffff8163772e: tty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tty_lock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_mutex.c (ffffffff8166b9c0)
Location: drivers/tty/tty_mutex.c:14
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write_message
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_mutex.c:tty_lock_slave
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
```
**Symbols:**

```
ffffffff8166b9c0-ffffffff8166b9fe: tty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tty_lock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_mutex.c (ffffffff8168e030)
Location: drivers/tty/tty_mutex.c:14
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write_message
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_mutex.c:tty_lock_slave
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
```
**Symbols:**

```
ffffffff8168e030-ffffffff8168e06e: tty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tty_lock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_mutex.c (ffffffff81740280)
Location: drivers/tty/tty_mutex.c:14
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write_message
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_mutex.c:tty_lock_slave
  - drivers/tty/tty_jobctrl.c:tiocsctty
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
```
**Symbols:**

```
ffffffff81740280-ffffffff817402f9: tty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tty_lock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_mutex.c (ffffffff8175c1b0)
Location: drivers/tty/tty_mutex.c:14
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write_message
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_mutex.c:tty_lock_slave
  - drivers/tty/tty_jobctrl.c:tiocsctty
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
```
**Symbols:**

```
ffffffff8175c1b0-ffffffff8175c229: tty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tty_lock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_mutex.c (ffffffff81740050)
Location: drivers/tty/tty_mutex.c:15
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write_message
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_mutex.c:tty_lock_slave
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
```
**Symbols:**

```
ffffffff81740050-ffffffff817400c9: tty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tty_lock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_mutex.c (ffffffff817c07f0)
Location: drivers/tty/tty_mutex.c:15
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write_message
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_mutex.c:tty_lock_slave
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
```
**Symbols:**

```
ffffffff817c07f0-ffffffff817c0869: tty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tty_lock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_mutex.c (ffffffff818fd040)
Location: drivers/tty/tty_mutex.c:15
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write_message
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_mutex.c:tty_lock_slave
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
```
**Symbols:**

```
ffffffff818fd040-ffffffff818fd0cc: tty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tty_lock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_mutex.c (ffffffff81a56710)
Location: drivers/tty/tty_mutex.c:15
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write_message
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_mutex.c:tty_lock_slave
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
```
**Symbols:**

```
ffffffff81a56710-ffffffff81a56775: tty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tty_lock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_mutex.c (ffffffff81aa0cf0)
Location: drivers/tty/tty_mutex.c:15
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write_message
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_mutex.c:tty_lock_slave
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
```
**Symbols:**

```
ffffffff81aa0cf0-ffffffff81aa0d55: tty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tty_lock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_mutex.c (ffffffff81af3750)
Location: drivers/tty/tty_mutex.c:15
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_mutex.c:tty_lock_slave
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
```
**Symbols:**

```
ffffffff81af3750-ffffffff81af37b5: tty_lock (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void tty_lock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_mutex.c (ffff80001085f198)
Location: drivers/tty/tty_mutex.c:14
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write_message
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_mutex.c:tty_lock_slave
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
```
**Symbols:**

```
ffff80001085f198-ffff80001085f200: tty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tty_lock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_mutex.c (c0966654)
Location: drivers/tty/tty_mutex.c:14
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write_message
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_mutex.c:tty_lock_slave
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
```
**Symbols:**

```
c0966654-c09666c8: tty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tty_lock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_mutex.c (c0000000008fe680)
Location: drivers/tty/tty_mutex.c:14
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write_message
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_mutex.c:tty_lock_slave
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
```
**Symbols:**

```
c0000000008fe680-c0000000008fe708: tty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tty_lock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_mutex.c (ffffffe0005376a8)
Location: drivers/tty/tty_mutex.c:14
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write_message
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_mutex.c:tty_lock_slave
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
```
**Symbols:**

```
ffffffe0005376a8-ffffffe00053770a: tty_lock (STB_GLOBAL)
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
void tty_lock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_mutex.c (ffffffff81653ab0)
Location: drivers/tty/tty_mutex.c:14
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write_message
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_mutex.c:tty_lock_slave
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
```
**Symbols:**

```
ffffffff81653ab0-ffffffff81653aee: tty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tty_lock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_mutex.c (ffffffff81633e90)
Location: drivers/tty/tty_mutex.c:14
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write_message
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_mutex.c:tty_lock_slave
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff81633e90-ffffffff81633ece: tty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tty_lock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_mutex.c (ffffffff81681e70)
Location: drivers/tty/tty_mutex.c:14
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write_message
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_mutex.c:tty_lock_slave
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
```
**Symbols:**

```
ffffffff81681e70-ffffffff81681eae: tty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tty_lock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_mutex.c (ffffffff8169c4b0)
Location: drivers/tty/tty_mutex.c:14
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write_message
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_mutex.c:tty_lock_slave
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
```
**Symbols:**

```
ffffffff8169c4b0-ffffffff8169c4ee: tty_lock (STB_GLOBAL)
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
