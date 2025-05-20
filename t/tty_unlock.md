# Function: <code>tty_unlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void tty_unlock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_mutex.c (ffffffff81824350)
Location: drivers/tty/tty_mutex.c:33
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:__tty_hangup
  - drivers/tty/tty_io.c:__tty_hangup
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_write_message
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_mutex.c:tty_unlock_slave
```
**Symbols:**

```
ffffffff81824350-ffffffff8182439e: tty_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tty_unlock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_mutex.c (ffffffff8153ca60)
Location: drivers/tty/tty_mutex.c:35
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write_message
  - drivers/tty/tty_io.c:__tty_hangup
  - drivers/tty/tty_io.c:__tty_hangup
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_mutex.c:tty_unlock_slave
```
**Symbols:**

```
ffffffff8153ca60-ffffffff8153caaa: tty_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tty_unlock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_mutex.c (ffffffff815690b0)
Location: drivers/tty/tty_mutex.c:35
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write_message
  - drivers/tty/tty_io.c:__tty_hangup
  - drivers/tty/tty_io.c:__tty_hangup
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_mutex.c:tty_unlock_slave
```
**Symbols:**

```
ffffffff815690b0-ffffffff815690fa: tty_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tty_unlock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_mutex.c (ffffffff8157c6e0)
Location: drivers/tty/tty_mutex.c:35
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open_by_driver
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write_message
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_mutex.c:tty_unlock_slave
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff8157c6e0-ffffffff8157c720: tty_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tty_unlock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_mutex.c (ffffffff815e11a0)
Location: drivers/tty/tty_mutex.c:36
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write_message
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_mutex.c:tty_unlock_slave
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff815e11a0-ffffffff815e11e0: tty_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tty_unlock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_mutex.c (ffffffff8161a430)
Location: drivers/tty/tty_mutex.c:36
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write_message
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_mutex.c:tty_unlock_slave
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff8161a430-ffffffff8161a46f: tty_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tty_unlock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_mutex.c (ffffffff816376b0)
Location: drivers/tty/tty_mutex.c:36
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write_message
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_mutex.c:tty_unlock_slave
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff816376b0-ffffffff816376ef: tty_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tty_unlock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_mutex.c (ffffffff8166b970)
Location: drivers/tty/tty_mutex.c:36
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write_message
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_mutex.c:tty_unlock_slave
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff8166b970-ffffffff8166b9b3: tty_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tty_unlock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_mutex.c (ffffffff8168dfe0)
Location: drivers/tty/tty_mutex.c:36
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write_message
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_mutex.c:tty_unlock_slave
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff8168dfe0-ffffffff8168e023: tty_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tty_unlock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_mutex.c (ffffffff81740230)
Location: drivers/tty/tty_mutex.c:36
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open_by_driver
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write_message
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_mutex.c:tty_unlock_slave
  - drivers/tty/tty_jobctrl.c:tiocsctty
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff81740230-ffffffff81740277: tty_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tty_unlock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_mutex.c (ffffffff8175c160)
Location: drivers/tty/tty_mutex.c:36
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open_by_driver
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write_message
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_mutex.c:tty_unlock_slave
  - drivers/tty/tty_jobctrl.c:tiocsctty
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff8175c160-ffffffff8175c1a7: tty_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tty_unlock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_mutex.c (ffffffff81740000)
Location: drivers/tty/tty_mutex.c:37
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write_message
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_mutex.c:tty_unlock_slave
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff81740000-ffffffff81740047: tty_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void tty_unlock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_mutex.c (ffffffff817c094c)
Location: drivers/tty/tty_mutex.c:37
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_unlock_slave
Direct callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write_message
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff817c07a0-ffffffff817c07e7: tty_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void tty_unlock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_mutex.c (ffffffff818fd1db)
Location: drivers/tty/tty_mutex.c:37
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_unlock_slave
Direct callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write_message
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff818fcfe0-ffffffff818fd036: tty_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void tty_unlock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_mutex.c (ffffffff81a5687b)
Location: drivers/tty/tty_mutex.c:33
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_unlock_slave
Direct callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write_message
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff81a566d0-ffffffff81a566fd: tty_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void tty_unlock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_mutex.c (ffffffff81aa0e5b)
Location: drivers/tty/tty_mutex.c:33
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_unlock_slave
Direct callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write_message
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff81aa0cb0-ffffffff81aa0cdd: tty_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void tty_unlock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_mutex.c (ffffffff81af38bb)
Location: drivers/tty/tty_mutex.c:33
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_unlock_slave
Direct callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff81af3710-ffffffff81af373d: tty_unlock (STB_GLOBAL)
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
void tty_unlock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_mutex.c (ffff80001085f200)
Location: drivers/tty/tty_mutex.c:36
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write_message
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_mutex.c:tty_unlock_slave
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffff80001085f200-ffff80001085f264: tty_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tty_unlock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_mutex.c (c09666c8)
Location: drivers/tty/tty_mutex.c:36
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write_message
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_mutex.c:tty_unlock_slave
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
c09666c8-c0966734: tty_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tty_unlock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_mutex.c (c0000000008fe710)
Location: drivers/tty/tty_mutex.c:36
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write_message
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_mutex.c:tty_unlock_slave
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
c0000000008fe710-c0000000008fe79c: tty_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tty_unlock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_mutex.c (ffffffe00053770a)
Location: drivers/tty/tty_mutex.c:36
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write_message
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_mutex.c:tty_unlock_slave
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffe00053770a-ffffffe00053776a: tty_unlock (STB_GLOBAL)
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
void tty_unlock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_mutex.c (ffffffff81653a60)
Location: drivers/tty/tty_mutex.c:36
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write_message
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_mutex.c:tty_unlock_slave
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff81653a60-ffffffff81653aa3: tty_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tty_unlock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_mutex.c (ffffffff81633e40)
Location: drivers/tty/tty_mutex.c:36
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write_message
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_mutex.c:tty_unlock_slave
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff81633e40-ffffffff81633e83: tty_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tty_unlock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_mutex.c (ffffffff81681e20)
Location: drivers/tty/tty_mutex.c:36
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write_message
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_mutex.c:tty_unlock_slave
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff81681e20-ffffffff81681e63: tty_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tty_unlock(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_mutex.c (ffffffff8169c460)
Location: drivers/tty/tty_mutex.c:36
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write_message
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_mutex.c:tty_unlock_slave
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff8169c460-ffffffff8169c4a3: tty_unlock (STB_GLOBAL)
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
