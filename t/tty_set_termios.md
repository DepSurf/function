# Function: <code>tty_set_termios</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tty_set_termios(struct tty_struct *tty, struct ktermios *new_termios);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff814e8700)
Location: drivers/tty/tty_ioctl.c:542
Inline: False
```
**Symbols:**

```
ffffffff814e8700-ffffffff814e8963: tty_set_termios (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tty_set_termios(struct tty_struct *tty, struct ktermios *new_termios);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81539850)
Location: drivers/tty/tty_ioctl.c:535
Inline: False
```
**Symbols:**

```
ffffffff81539850-ffffffff81539a88: tty_set_termios (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tty_set_termios(struct tty_struct *tty, struct ktermios *new_termios);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81565f30)
Location: drivers/tty/tty_ioctl.c:535
Inline: False
```
**Symbols:**

```
ffffffff81565f30-ffffffff81566168: tty_set_termios (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tty_set_termios(struct tty_struct *tty, struct ktermios *new_termios);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81579540)
Location: drivers/tty/tty_ioctl.c:313
Inline: False
```
**Symbols:**

```
ffffffff81579540-ffffffff81579766: tty_set_termios (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tty_set_termios(struct tty_struct *tty, struct ktermios *new_termios);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff815ddef0)
Location: drivers/tty/tty_ioctl.c:314
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff815ddef0-ffffffff815de11c: tty_set_termios (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tty_set_termios(struct tty_struct *tty, struct ktermios *new_termios);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81617220)
Location: drivers/tty/tty_ioctl.c:314
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff81617220-ffffffff81617456: tty_set_termios (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tty_set_termios(struct tty_struct *tty, struct ktermios *new_termios);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81634420)
Location: drivers/tty/tty_ioctl.c:314
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff81634420-ffffffff81634656: tty_set_termios (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int tty_set_termios(struct tty_struct *tty, struct ktermios *new_termios);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_ioctl.c (0)
Location: drivers/tty/tty_ioctl.c:314
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff816693f9-ffffffff8166940c: tty_set_termios.cold (STB_LOCAL)
ffffffff816684d0-ffffffff81668724: tty_set_termios (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tty_set_termios(struct tty_struct *tty, struct ktermios *new_termios);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff8168ac20)
Location: drivers/tty/tty_ioctl.c:314
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff8168ac20-ffffffff8168ae7b: tty_set_termios (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tty_set_termios(struct tty_struct *tty, struct ktermios *new_termios);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff8173cc70)
Location: drivers/tty/tty_ioctl.c:314
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff8173cc70-ffffffff8173cdfe: tty_set_termios (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tty_set_termios(struct tty_struct *tty, struct ktermios *new_termios);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81758c80)
Location: drivers/tty/tty_ioctl.c:314
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff81758c80-ffffffff81758e0e: tty_set_termios (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tty_set_termios(struct tty_struct *tty, struct ktermios *new_termios);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff8173cb20)
Location: drivers/tty/tty_ioctl.c:314
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff8173cb20-ffffffff8173cd8b: tty_set_termios (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tty_set_termios(struct tty_struct *tty, struct ktermios *new_termios);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff817bd120)
Location: drivers/tty/tty_ioctl.c:338
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff817bd120-ffffffff817bd41c: tty_set_termios (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tty_set_termios(struct tty_struct *tty, struct ktermios *new_termios);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff818f9400)
Location: drivers/tty/tty_ioctl.c:338
Inline: False
Direct callers:
  - drivers/tty/tty_ioctl.c:set_termios
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff818f9400-ffffffff818f9729: tty_set_termios (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tty_set_termios(struct tty_struct *tty, struct ktermios *new_termios);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81a522c0)
Location: drivers/tty/tty_ioctl.c:341
Inline: False
Direct callers:
  - drivers/tty/tty_ioctl.c:set_termios
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff81a522c0-ffffffff81a525fa: tty_set_termios (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tty_set_termios(struct tty_struct *tty, struct ktermios *new_termios);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81a9c5c0)
Location: drivers/tty/tty_ioctl.c:342
Inline: False
Direct callers:
  - drivers/tty/tty_ioctl.c:set_termios
  - drivers/tty/tty_ioctl.c:set_termios
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff81a9c5c0-ffffffff81a9c8f9: tty_set_termios (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tty_set_termios(struct tty_struct *tty, struct ktermios *new_termios);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81aef090)
Location: drivers/tty/tty_ioctl.c:323
Inline: False
Direct callers:
  - drivers/tty/tty_ioctl.c:set_termios
  - drivers/tty/tty_ioctl.c:set_termios
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff81aef090-ffffffff81aef3c9: tty_set_termios (STB_GLOBAL)
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
int tty_set_termios(struct tty_struct *tty, struct ktermios *new_termios);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffff800010859138)
Location: drivers/tty/tty_ioctl.c:314
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffff800010859138-ffff800010859348: tty_set_termios (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tty_set_termios(struct tty_struct *tty, struct ktermios *new_termios);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (c0962b9c)
Location: drivers/tty/tty_ioctl.c:314
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
c0962b9c-c0962da0: tty_set_termios (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tty_set_termios(struct tty_struct *tty, struct ktermios *new_termios);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (c0000000008f8cf0)
Location: drivers/tty/tty_ioctl.c:314
Inline: False
Direct callers:
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
c0000000008f8cf0-c0000000008f8f78: tty_set_termios (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tty_set_termios(struct tty_struct *tty, struct ktermios *new_termios);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffe0005342f4)
Location: drivers/tty/tty_ioctl.c:314
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffe0005342f4-ffffffe0005344c0: tty_set_termios (STB_GLOBAL)
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
int tty_set_termios(struct tty_struct *tty, struct ktermios *new_termios);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff816506a0)
Location: drivers/tty/tty_ioctl.c:314
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff816506a0-ffffffff816508fb: tty_set_termios (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tty_set_termios(struct tty_struct *tty, struct ktermios *new_termios);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81630af0)
Location: drivers/tty/tty_ioctl.c:314
Inline: False
```
**Symbols:**

```
ffffffff81630af0-ffffffff81630d4b: tty_set_termios (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tty_set_termios(struct tty_struct *tty, struct ktermios *new_termios);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff8167ea60)
Location: drivers/tty/tty_ioctl.c:314
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff8167ea60-ffffffff8167ecbb: tty_set_termios (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tty_set_termios(struct tty_struct *tty, struct ktermios *new_termios);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff816990b0)
Location: drivers/tty/tty_ioctl.c:314
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_parity
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_flow_control
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff816990b0-ffffffff8169930b: tty_set_termios (STB_GLOBAL)
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
