# Function: <code>user_termios_to_kernel_termios</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff814e8d49)
Location: include/asm-generic/termios.h:70
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81539ed3)
Location: include/asm-generic/termios.h:70
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
In drivers/tty/tty_ioctl.c (ffffffff815665a3)
Location: include/asm-generic/termios.h:70
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
In drivers/tty/tty_ioctl.c (ffffffff81579bc3)
Location: include/asm-generic/termios.h:70
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
In drivers/tty/tty_ioctl.c (ffffffff815de583)
Location: include/asm-generic/termios.h:71
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
In drivers/tty/tty_ioctl.c (ffffffff81617959)
Location: include/asm-generic/termios.h:71
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
In drivers/tty/tty_ioctl.c (ffffffff81634b59)
Location: include/asm-generic/termios.h:71
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
In drivers/tty/tty_ioctl.c (ffffffff81668c27)
Location: include/asm-generic/termios.h:71
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
In drivers/tty/tty_ioctl.c (ffffffff8168b377)
Location: include/asm-generic/termios.h:71
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
In drivers/tty/tty_ioctl.c (ffffffff8173d111)
Location: include/asm-generic/termios.h:71
Inline: True
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
In drivers/tty/tty_ioctl.c (ffffffff8175901c)
Location: include/asm-generic/termios.h:71
Inline: True
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
In drivers/tty/tty_ioctl.c (ffffffff8173cf9c)
Location: include/asm-generic/termios.h:71
Inline: True
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
In drivers/tty/tty_ioctl.c (ffffffff817bd62c)
Location: include/asm-generic/termios.h:71
Inline: True
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
In drivers/tty/tty_ioctl.c (ffffffff818f9993)
Location: include/asm-generic/termios.h:71
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:set_termios
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int user_termios_to_kernel_termios(struct ktermios *k, struct termios2 *u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81a52980)
Location: drivers/tty/tty_ioctl.c:417
Inline: False
Direct callers:
  - drivers/tty/tty_ioctl.c:set_termios
```
**Symbols:**

```
ffffffff81a52980-ffffffff81a5299f: user_termios_to_kernel_termios (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int user_termios_to_kernel_termios(struct ktermios *k, struct termios2 *u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81a9cc80)
Location: drivers/tty/tty_ioctl.c:418
Inline: False
Direct callers:
  - drivers/tty/tty_ioctl.c:set_termios
```
**Symbols:**

```
ffffffff81a9cc80-ffffffff81a9cc9f: user_termios_to_kernel_termios (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int user_termios_to_kernel_termios(struct ktermios *k, struct termios2 *u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81aef750)
Location: drivers/tty/tty_ioctl.c:399
Inline: False
Direct callers:
  - drivers/tty/tty_ioctl.c:set_termios
```
**Symbols:**

```
ffffffff81aef750-ffffffff81aef76f: user_termios_to_kernel_termios (STB_WEAK)
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
In drivers/tty/tty_ioctl.c (ffff80001085a448)
Location: include/asm-generic/termios.h:71
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
In drivers/tty/tty_ioctl.c (c09635e0)
Location: include/asm-generic/termios.h:71
Inline: True
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffe0005348ea)
Location: include/asm-generic/termios.h:71
Inline: True
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
In drivers/tty/tty_ioctl.c (ffffffff81650df7)
Location: include/asm-generic/termios.h:71
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
In drivers/tty/tty_ioctl.c (ffffffff81631247)
Location: include/asm-generic/termios.h:71
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
In drivers/tty/tty_ioctl.c (ffffffff8167f1b7)
Location: include/asm-generic/termios.h:71
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
In drivers/tty/tty_ioctl.c (ffffffff81699807)
Location: include/asm-generic/termios.h:71
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
