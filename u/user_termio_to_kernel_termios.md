# Function: <code>user_termio_to_kernel_termios</code>

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
In drivers/tty/tty_ioctl.c (ffffffff814e8e1d)
Location: include/asm-generic/termios.h:19
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
In drivers/tty/tty_ioctl.c (ffffffff81539fa5)
Location: include/asm-generic/termios.h:19
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
In drivers/tty/tty_ioctl.c (ffffffff8156666c)
Location: include/asm-generic/termios.h:19
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
In drivers/tty/tty_ioctl.c (ffffffff81579c5e)
Location: include/asm-generic/termios.h:19
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
In drivers/tty/tty_ioctl.c (ffffffff815de621)
Location: include/asm-generic/termios.h:20
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
In drivers/tty/tty_ioctl.c (ffffffff81617963)
Location: include/asm-generic/termios.h:20
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
In drivers/tty/tty_ioctl.c (ffffffff81634b63)
Location: include/asm-generic/termios.h:20
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
In drivers/tty/tty_ioctl.c (ffffffff81668c31)
Location: include/asm-generic/termios.h:20
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
In drivers/tty/tty_ioctl.c (ffffffff8168b381)
Location: include/asm-generic/termios.h:20
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
In drivers/tty/tty_ioctl.c (ffffffff8173d11b)
Location: include/asm-generic/termios.h:20
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
In drivers/tty/tty_ioctl.c (ffffffff81759026)
Location: include/asm-generic/termios.h:20
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
In drivers/tty/tty_ioctl.c (ffffffff8173cfa6)
Location: include/asm-generic/termios.h:20
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
In drivers/tty/tty_ioctl.c (ffffffff817bd636)
Location: include/asm-generic/termios.h:20
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
In drivers/tty/tty_ioctl.c (ffffffff818f999d)
Location: include/asm-generic/termios.h:20
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
int user_termio_to_kernel_termios(struct ktermios *termios, struct termio *termio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81a52810)
Location: drivers/tty/tty_ioctl.c:382
Inline: False
Direct callers:
  - drivers/tty/tty_ioctl.c:set_termios
```
**Symbols:**

```
ffffffff81a52810-ffffffff81a528b4: user_termio_to_kernel_termios (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int user_termio_to_kernel_termios(struct ktermios *termios, struct termio *termio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81a9cb10)
Location: drivers/tty/tty_ioctl.c:383
Inline: False
Direct callers:
  - drivers/tty/tty_ioctl.c:set_termios
```
**Symbols:**

```
ffffffff81a9cb10-ffffffff81a9cbb4: user_termio_to_kernel_termios (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int user_termio_to_kernel_termios(struct ktermios *termios, struct termio *termio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81aef5e0)
Location: drivers/tty/tty_ioctl.c:364
Inline: False
Direct callers:
  - drivers/tty/tty_ioctl.c:set_termios
```
**Symbols:**

```
ffffffff81aef5e0-ffffffff81aef684: user_termio_to_kernel_termios (STB_WEAK)
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
int user_termio_to_kernel_termios(struct ktermios *termios, const struct termio *termio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffff800010859a88)
Location: include/asm-generic/termios.h:20
Inline: False
```
**Symbols:**

```
ffff800010859a88-ffff80001085a224: user_termio_to_kernel_termios (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int user_termio_to_kernel_termios(struct ktermios *termios, const struct termio *termio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (c0963300)
Location: include/asm-generic/termios.h:20
Inline: False
```
**Symbols:**

```
c0963300-c0963524: user_termio_to_kernel_termios (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int user_termio_to_kernel_termios(struct ktermios *termios, struct termio *termio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (c0000000008f9540)
Location: include/asm-generic/termios-base.h:15
Inline: False
```
**Symbols:**

```
c0000000008f9540-c0000000008f983c: user_termio_to_kernel_termios (STB_LOCAL)
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
In drivers/tty/tty_ioctl.c (ffffffe000534968)
Location: include/asm-generic/termios.h:20
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
In drivers/tty/tty_ioctl.c (ffffffff81650e01)
Location: include/asm-generic/termios.h:20
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
In drivers/tty/tty_ioctl.c (ffffffff81631251)
Location: include/asm-generic/termios.h:20
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
In drivers/tty/tty_ioctl.c (ffffffff8167f1c1)
Location: include/asm-generic/termios.h:20
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
In drivers/tty/tty_ioctl.c (ffffffff81699811)
Location: include/asm-generic/termios.h:20
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
<b>Arch</b>
<ul>
</ul>
