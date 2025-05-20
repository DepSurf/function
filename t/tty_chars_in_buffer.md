# Function: <code>tty_chars_in_buffer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int tty_chars_in_buffer(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff814e8100)
Location: drivers/tty/tty_ioctl.c:55
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
Direct callers:
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/n_tty.c:n_tty_ioctl
  - drivers/tty/vt/keyboard.c:kbd_event
```
**Symbols:**

```
ffffffff814e8100-ffffffff814e811d: tty_chars_in_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int tty_chars_in_buffer(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81539707)
Location: drivers/tty/tty_ioctl.c:55
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
Direct callers:
  - drivers/tty/n_tty.c:n_tty_ioctl
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/vt/keyboard.c:kbd_event
```
**Symbols:**

```
ffffffff81539260-ffffffff8153927d: tty_chars_in_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int tty_chars_in_buffer(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81565e13)
Location: drivers/tty/tty_ioctl.c:55
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
Direct callers:
  - drivers/tty/n_tty.c:n_tty_ioctl
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/vt/keyboard.c:kbd_event
```
**Symbols:**

```
ffffffff81565970-ffffffff8156598d: tty_chars_in_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int tty_chars_in_buffer(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff815793e3)
Location: drivers/tty/tty_ioctl.c:55
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
Direct callers:
  - drivers/tty/n_tty.c:n_tty_ioctl
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/vt/keyboard.c:kbd_event
```
**Symbols:**

```
ffffffff81579170-ffffffff8157918d: tty_chars_in_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int tty_chars_in_buffer(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff815ddd93)
Location: drivers/tty/tty_ioctl.c:56
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
Direct callers:
  - drivers/tty/n_tty.c:n_tty_ioctl
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/vt/keyboard.c:kbd_event
```
**Symbols:**

```
ffffffff815ddb00-ffffffff815ddb20: tty_chars_in_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int tty_chars_in_buffer(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff816170c7)
Location: drivers/tty/tty_ioctl.c:56
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
Direct callers:
  - drivers/tty/n_tty.c:n_tty_ioctl
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/vt/keyboard.c:kbd_event
```
**Symbols:**

```
ffffffff81616dc0-ffffffff81616de0: tty_chars_in_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int tty_chars_in_buffer(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff816342c7)
Location: drivers/tty/tty_ioctl.c:56
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
Direct callers:
  - drivers/tty/n_tty.c:n_tty_ioctl
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/vt/keyboard.c:kbd_event
```
**Symbols:**

```
ffffffff81633fc0-ffffffff81633fe0: tty_chars_in_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int tty_chars_in_buffer(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81668377)
Location: drivers/tty/tty_ioctl.c:56
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
Direct callers:
  - drivers/tty/n_tty.c:n_tty_ioctl
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/vt/keyboard.c:kbd_keycode
```
**Symbols:**

```
ffffffff81668070-ffffffff81668090: tty_chars_in_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int tty_chars_in_buffer(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff8168aac7)
Location: drivers/tty/tty_ioctl.c:56
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
Direct callers:
  - drivers/tty/n_tty.c:n_tty_ioctl
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/vt/keyboard.c:kbd_keycode
```
**Symbols:**

```
ffffffff8168a7c0-ffffffff8168a7e0: tty_chars_in_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int tty_chars_in_buffer(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff8173cb17)
Location: drivers/tty/tty_ioctl.c:56
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
Direct callers:
  - drivers/tty/n_tty.c:n_tty_ioctl
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/vt/keyboard.c:kbd_keycode
```
**Symbols:**

```
ffffffff8173c6b0-ffffffff8173c6d0: tty_chars_in_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int tty_chars_in_buffer(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81758b27)
Location: drivers/tty/tty_ioctl.c:56
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
Direct callers:
  - drivers/tty/n_tty.c:n_tty_ioctl
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/vt/keyboard.c:kbd_keycode
```
**Symbols:**

```
ffffffff81758820-ffffffff81758840: tty_chars_in_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int tty_chars_in_buffer(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff8173c9c7)
Location: drivers/tty/tty_ioctl.c:57
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
Direct callers:
  - drivers/tty/n_tty.c:n_tty_ioctl
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/vt/keyboard.c:kbd_keycode
```
**Symbols:**

```
ffffffff8173c780-ffffffff8173c7a0: tty_chars_in_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
unsigned int tty_chars_in_buffer(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff817bcfc7)
Location: drivers/tty/tty_ioctl.c:57
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
Direct callers:
  - drivers/tty/n_tty.c:n_tty_ioctl
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/vt/keyboard.c:kbd_keycode
```
**Symbols:**

```
ffffffff817bcd50-ffffffff817bcd70: tty_chars_in_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
unsigned int tty_chars_in_buffer(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff818f9267)
Location: drivers/tty/tty_ioctl.c:57
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
Direct callers:
  - drivers/tty/n_tty.c:n_tty_ioctl
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/vt/keyboard.c:kbd_keycode
```
**Symbols:**

```
ffffffff818f8f70-ffffffff818f8fa0: tty_chars_in_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
unsigned int tty_chars_in_buffer(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81a52117)
Location: drivers/tty/tty_ioctl.c:58
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
Direct callers:
  - drivers/tty/n_tty.c:n_tty_ioctl
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/vt/keyboard.c:kbd_keycode
```
**Symbols:**

```
ffffffff81a51d90-ffffffff81a51dc0: tty_chars_in_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
unsigned int tty_chars_in_buffer(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81a9cfb4)
Location: drivers/tty/tty_ioctl.c:59
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:set_termios
  - drivers/tty/tty_ioctl.c:set_termios
  - drivers/tty/tty_ioctl.c:set_termios
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
Direct callers:
  - drivers/tty/n_tty.c:n_tty_ioctl
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/vt/keyboard.c:kbd_keycode
```
**Symbols:**

```
ffffffff81a9c0a0-ffffffff81a9c0d0: tty_chars_in_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int tty_chars_in_buffer(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81aefa84)
Location: drivers/tty/tty_ioctl.c:48
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:set_termios
  - drivers/tty/tty_ioctl.c:set_termios
  - drivers/tty/tty_ioctl.c:set_termios
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
Direct callers:
  - drivers/tty/n_tty.c:n_tty_ioctl
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/vt/keyboard.c:kbd_keycode
```
**Symbols:**

```
ffffffff81aeeb70-ffffffff81aeeba0: tty_chars_in_buffer (STB_GLOBAL)
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
int tty_chars_in_buffer(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffff800010858fd8)
Location: drivers/tty/tty_ioctl.c:56
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
Direct callers:
  - drivers/tty/n_tty.c:n_tty_ioctl
  - drivers/tty/n_tty.c:n_tty_poll
```
**Symbols:**

```
ffff800010858d58-ffff800010858d94: tty_chars_in_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int tty_chars_in_buffer(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (c0962a44)
Location: drivers/tty/tty_ioctl.c:56
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
Direct callers:
  - drivers/tty/n_tty.c:n_tty_ioctl
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/vt/keyboard.c:kbd_keycode
```
**Symbols:**

```
c0962740-c0962774: tty_chars_in_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int tty_chars_in_buffer(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (c0000000008f8ae4)
Location: drivers/tty/tty_ioctl.c:56
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
Direct callers:
  - drivers/tty/n_tty.c:n_tty_ioctl
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/vt/keyboard.c:kbd_keycode
```
**Symbols:**

```
c0000000008f87e0-c0000000008f8838: tty_chars_in_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int tty_chars_in_buffer(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffe000534224)
Location: drivers/tty/tty_ioctl.c:56
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
Direct callers:
  - drivers/tty/n_tty.c:n_tty_ioctl
  - drivers/tty/n_tty.c:n_tty_poll
```
**Symbols:**

```
ffffffe000533f5e-ffffffe000533f8a: tty_chars_in_buffer (STB_GLOBAL)
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
int tty_chars_in_buffer(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81650547)
Location: drivers/tty/tty_ioctl.c:56
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
Direct callers:
  - drivers/tty/n_tty.c:n_tty_ioctl
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/vt/keyboard.c:kbd_keycode
```
**Symbols:**

```
ffffffff81650240-ffffffff81650260: tty_chars_in_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int tty_chars_in_buffer(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81630997)
Location: drivers/tty/tty_ioctl.c:56
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
Direct callers:
  - drivers/tty/n_tty.c:n_tty_ioctl
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/vt/keyboard.c:kbd_keycode
```
**Symbols:**

```
ffffffff81630690-ffffffff816306b0: tty_chars_in_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int tty_chars_in_buffer(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff8167e907)
Location: drivers/tty/tty_ioctl.c:56
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
Direct callers:
  - drivers/tty/n_tty.c:n_tty_ioctl
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/vt/keyboard.c:kbd_keycode
```
**Symbols:**

```
ffffffff8167e600-ffffffff8167e620: tty_chars_in_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int tty_chars_in_buffer(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81698f66)
Location: drivers/tty/tty_ioctl.c:56
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
Direct callers:
  - drivers/tty/n_tty.c:n_tty_ioctl
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/vt/keyboard.c:kbd_keycode
```
**Symbols:**

```
ffffffff81698c60-ffffffff81698c80: tty_chars_in_buffer (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>unsigned int</code>
</li>
</ul>
</details>
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
