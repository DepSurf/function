# Function: <code>tty_wakeup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tty_wakeup(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff814df9a0)
Location: drivers/tty/tty_io.c:586
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_port.c:tty_port_tty_wakeup
  - drivers/tty/pty.c:pty_unthrottle
  - drivers/tty/hvc/hvc_console.c:hvc_poll
```
**Symbols:**

```
ffffffff814df9a0-ffffffff814dfa02: tty_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tty_wakeup(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81530960)
Location: drivers/tty/tty_io.c:593
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_port.c:tty_port_tty_wakeup
  - drivers/tty/pty.c:pty_unthrottle
  - drivers/tty/hvc/hvc_console.c:hvc_poll
  - drivers/tty/serial/serial_core.c:uart_flush_buffer
```
**Symbols:**

```
ffffffff81530960-ffffffff815309c2: tty_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tty_wakeup(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8155d0b0)
Location: drivers/tty/tty_io.c:593
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_port.c:tty_port_tty_wakeup
  - drivers/tty/pty.c:pty_unthrottle
  - drivers/tty/hvc/hvc_console.c:hvc_poll
```
**Symbols:**

```
ffffffff8155d0b0-ffffffff8155d112: tty_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tty_wakeup(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81571d80)
Location: drivers/tty/tty_io.c:512
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/pty.c:pty_unthrottle
  - drivers/tty/hvc/hvc_console.c:hvc_poll
```
**Symbols:**

```
ffffffff81571d80-ffffffff81571de2: tty_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tty_wakeup(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815d6300)
Location: drivers/tty/tty_io.c:524
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/pty.c:pty_unthrottle
  - drivers/tty/hvc/hvc_console.c:hvc_poll
  - drivers/usb/host/xhci-dbgtty.c:dbc_start_tx
```
**Symbols:**

```
ffffffff815d6300-ffffffff815d6365: tty_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tty_wakeup(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8160f330)
Location: drivers/tty/tty_io.c:524
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/pty.c:pty_unthrottle
  - drivers/tty/hvc/hvc_console.c:hvc_poll
  - drivers/usb/host/xhci-dbgtty.c:dbc_start_tx
```
**Symbols:**

```
ffffffff8160f330-ffffffff8160f395: tty_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tty_wakeup(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8162c2e0)
Location: drivers/tty/tty_io.c:525
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/pty.c:pty_unthrottle
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/usb/host/xhci-dbgtty.c:dbc_start_tx
```
**Symbols:**

```
ffffffff8162c2e0-ffffffff8162c345: tty_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tty_wakeup(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81660230)
Location: drivers/tty/tty_io.c:527
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/pty.c:pty_unthrottle
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/usb/host/xhci-dbgtty.c:dbc_start_tx
```
**Symbols:**

```
ffffffff81660230-ffffffff81660295: tty_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tty_wakeup(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81682880)
Location: drivers/tty/tty_io.c:527
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/pty.c:pty_unthrottle
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/usb/host/xhci-dbgtty.c:dbc_start_tx
```
**Symbols:**

```
ffffffff81682880-ffffffff816828e5: tty_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tty_wakeup(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81733bc0)
Location: drivers/tty/tty_io.c:528
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:start_tty
  - drivers/tty/n_tty.c:n_tty_check_unthrottle
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/pty.c:pty_unthrottle
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
**Symbols:**

```
ffffffff81733bc0-ffffffff81733c25: tty_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tty_wakeup(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8174fd10)
Location: drivers/tty/tty_io.c:525
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:start_tty
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/pty.c:pty_unthrottle
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
**Symbols:**

```
ffffffff8174fd10-ffffffff8174fd75: tty_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tty_wakeup(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81733c80)
Location: drivers/tty/tty_io.c:526
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:start_tty
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/pty.c:pty_unthrottle
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
**Symbols:**

```
ffffffff81733c80-ffffffff81733ce5: tty_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tty_wakeup(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817b45f0)
Location: drivers/tty/tty_io.c:526
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/pty.c:pty_unthrottle
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
**Symbols:**

```
ffffffff817b45f0-ffffffff817b4655: tty_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tty_wakeup(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff818f03a0)
Location: drivers/tty/tty_io.c:522
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/pty.c:pty_unthrottle
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
**Symbols:**

```
ffffffff818f03a0-ffffffff818f0413: tty_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tty_wakeup(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a484e0)
Location: drivers/tty/tty_io.c:516
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/pty.c:pty_unthrottle
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
**Symbols:**

```
ffffffff81a484e0-ffffffff81a48553: tty_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tty_wakeup(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a92730)
Location: drivers/tty/tty_io.c:517
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/pty.c:pty_unthrottle
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
**Symbols:**

```
ffffffff81a92730-ffffffff81a927a3: tty_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tty_wakeup(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81ae5180)
Location: drivers/tty/tty_io.c:515
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/pty.c:pty_unthrottle
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
**Symbols:**

```
ffffffff81ae5180-ffffffff81ae51f3: tty_wakeup (STB_GLOBAL)
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
void tty_wakeup(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffff80001084e9d0)
Location: drivers/tty/tty_io.c:527
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/pty.c:pty_unthrottle
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/usb/host/xhci-dbgtty.c:dbc_start_tx
```
**Symbols:**

```
ffff80001084e9d0-ffff80001084ea60: tty_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tty_wakeup(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c095aa00)
Location: drivers/tty/tty_io.c:527
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/pty.c:pty_unthrottle
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/usb/host/xhci-dbgtty.c:dbc_start_tx
```
**Symbols:**

```
c095aa00-c095aa6c: tty_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tty_wakeup(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c0000000008ed880)
Location: drivers/tty/tty_io.c:527
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/pty.c:pty_unthrottle
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/usb/host/xhci-dbgtty.c:dbc_start_tx
```
**Symbols:**

```
c0000000008ed880-c0000000008ed958: tty_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tty_wakeup(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffe00052ce32)
Location: drivers/tty/tty_io.c:527
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/pty.c:pty_unthrottle
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/usb/host/xhci-dbgtty.c:dbc_start_tx
```
**Symbols:**

```
ffffffe00052ce32-ffffffe00052ce96: tty_wakeup (STB_GLOBAL)
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
void tty_wakeup(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81648300)
Location: drivers/tty/tty_io.c:527
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/pty.c:pty_unthrottle
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
**Symbols:**

```
ffffffff81648300-ffffffff81648365: tty_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tty_wakeup(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81628760)
Location: drivers/tty/tty_io.c:527
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/pty.c:pty_unthrottle
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/usb/host/xhci-dbgtty.c:dbc_start_tx
```
**Symbols:**

```
ffffffff81628760-ffffffff816287c5: tty_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tty_wakeup(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff816766c0)
Location: drivers/tty/tty_io.c:527
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/pty.c:pty_unthrottle
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/usb/host/xhci-dbgtty.c:dbc_start_tx
```
**Symbols:**

```
ffffffff816766c0-ffffffff81676725: tty_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tty_wakeup(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81690de0)
Location: drivers/tty/tty_io.c:527
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/pty.c:pty_unthrottle
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/usb/host/xhci-dbgtty.c:dbc_start_tx
```
**Symbols:**

```
ffffffff81690de0-ffffffff81690e45: tty_wakeup (STB_GLOBAL)
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
