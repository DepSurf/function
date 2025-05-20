# Function: <code>tty_schedule_flip</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void tty_schedule_flip(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff814ea5f9)
Location: drivers/tty/tty_buffer.c:398
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_flip_buffer_push
Direct callers:
  - drivers/tty/vt/keyboard.c:puts_queue
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:k_shift
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/vt.c:respond_string
```
**Symbols:**

```
ffffffff814ea620-ffffffff814ea630: tty_schedule_flip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void tty_schedule_flip(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8153b5c9)
Location: drivers/tty/tty_buffer.c:373
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_flip_buffer_push
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:k_shift
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:puts_queue
  - drivers/tty/vt/vt.c:respond_string
```
**Symbols:**

```
ffffffff8153b5f0-ffffffff8153b600: tty_schedule_flip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void tty_schedule_flip(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff81567c59)
Location: drivers/tty/tty_buffer.c:373
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_flip_buffer_push
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:k_shift
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:puts_queue
  - drivers/tty/vt/vt.c:respond_string
```
**Symbols:**

```
ffffffff81567c80-ffffffff81567c90: tty_schedule_flip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void tty_schedule_flip(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8157b209)
Location: drivers/tty/tty_buffer.c:399
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_flip_buffer_push
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:k_shift
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:puts_queue
  - drivers/tty/vt/vt.c:respond_string
```
**Symbols:**

```
ffffffff8157b230-ffffffff8157b240: tty_schedule_flip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void tty_schedule_flip(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff815dfc19)
Location: drivers/tty/tty_buffer.c:400
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_flip_buffer_push
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:k_shift
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:puts_queue
  - drivers/tty/vt/vt.c:respond_string
```
**Symbols:**

```
ffffffff815dfc40-ffffffff815dfc50: tty_schedule_flip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void tty_schedule_flip(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff81618e95)
Location: drivers/tty/tty_buffer.c:400
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_flip_buffer_push
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:k_shift
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:puts_queue
  - drivers/tty/vt/vt.c:respond_string
```
**Symbols:**

```
ffffffff81618ec0-ffffffff81618ed0: tty_schedule_flip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void tty_schedule_flip(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff816360a5)
Location: drivers/tty/tty_buffer.c:405
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_flip_buffer_push
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:k_shift
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:puts_queue
  - drivers/tty/vt/vt.c:respond_string
```
**Symbols:**

```
ffffffff816360d0-ffffffff816360e0: tty_schedule_flip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void tty_schedule_flip(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8166a2e5)
Location: drivers/tty/tty_buffer.c:405
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_flip_buffer_push
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:k_shift
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:puts_queue
  - drivers/tty/vt/vt.c:respond_string
```
**Symbols:**

```
ffffffff8166a2b0-ffffffff8166a2dd: tty_schedule_flip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void tty_schedule_flip(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8168c9d5)
Location: drivers/tty/tty_buffer.c:405
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_flip_buffer_push
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:k_shift
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:puts_queue
  - drivers/tty/vt/vt.c:respond_string
```
**Symbols:**

```
ffffffff8168c9a0-ffffffff8168c9cd: tty_schedule_flip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void tty_schedule_flip(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8173ef95)
Location: drivers/tty/tty_buffer.c:405
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_flip_buffer_push
Direct callers:
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:puts_queue
  - drivers/tty/vt/keyboard.c:put_queue
  - drivers/tty/vt/keyboard.c:put_queue
  - drivers/tty/vt/vt.c:respond_string
```
**Symbols:**

```
ffffffff8173ea00-ffffffff8173ea2d: tty_schedule_flip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void tty_schedule_flip(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8175aec5)
Location: drivers/tty/tty_buffer.c:405
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_flip_buffer_push
Direct callers:
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:puts_queue
  - drivers/tty/vt/keyboard.c:put_queue
  - drivers/tty/vt/keyboard.c:put_queue
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:mouse_report
```
**Symbols:**

```
ffffffff8175a950-ffffffff8175a97d: tty_schedule_flip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void tty_schedule_flip(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8173ed65)
Location: drivers/tty/tty_buffer.c:405
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_flip_buffer_push
Direct callers:
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:puts_queue
  - drivers/tty/vt/keyboard.c:put_queue
  - drivers/tty/vt/keyboard.c:put_queue
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:mouse_report
```
**Symbols:**

```
ffffffff8173e7f0-ffffffff8173e81d: tty_schedule_flip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void tty_schedule_flip(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff817bf4f5)
Location: drivers/tty/tty_buffer.c:413
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_flip_buffer_push
Direct callers:
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:puts_queue
  - drivers/tty/vt/keyboard.c:put_queue
  - drivers/tty/vt/keyboard.c:put_queue
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:mouse_report
```
**Symbols:**

```
ffffffff817bef70-ffffffff817bef9d: tty_schedule_flip (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void tty_schedule_flip(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffff80001085d060)
Location: drivers/tty/tty_buffer.c:405
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_flip_buffer_push
Direct callers:
  - drivers/tty/vt/keyboard.c:k_shift
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:puts_queue
  - drivers/tty/vt/vt.c:respond_string
```
**Symbols:**

```
ffff80001085d090-ffff80001085d0b8: tty_schedule_flip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void tty_schedule_flip(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (c0964ed0)
Location: drivers/tty/tty_buffer.c:405
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_flip_buffer_push
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:k_shift
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:puts_queue
  - drivers/tty/vt/vt.c:respond_string
```
**Symbols:**

```
c0964efc-c0964f1c: tty_schedule_flip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void tty_schedule_flip(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (c0000000008fc20c)
Location: drivers/tty/tty_buffer.c:405
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_flip_buffer_push
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:k_shift
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:puts_queue
  - drivers/tty/vt/vt.c:respond_string
```
**Symbols:**

```
c0000000008fc190-c0000000008fc1e8: tty_schedule_flip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void tty_schedule_flip(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffe000535fe2)
Location: drivers/tty/tty_buffer.c:405
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_flip_buffer_push
Direct callers:
  - drivers/tty/vt/keyboard.c:k_shift
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:puts_queue
  - drivers/tty/vt/vt.c:respond_string
```
**Symbols:**

```
ffffffe00053600c-ffffffe000536034: tty_schedule_flip (STB_GLOBAL)
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
void tty_schedule_flip(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff81652455)
Location: drivers/tty/tty_buffer.c:405
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_flip_buffer_push
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:k_shift
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:puts_queue
  - drivers/tty/vt/vt.c:respond_string
```
**Symbols:**

```
ffffffff81652420-ffffffff8165244d: tty_schedule_flip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void tty_schedule_flip(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff81632895)
Location: drivers/tty/tty_buffer.c:405
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_flip_buffer_push
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:k_shift
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:puts_queue
  - drivers/tty/vt/vt.c:respond_string
```
**Symbols:**

```
ffffffff81632860-ffffffff8163288d: tty_schedule_flip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void tty_schedule_flip(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff81680815)
Location: drivers/tty/tty_buffer.c:405
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_flip_buffer_push
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:k_shift
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:puts_queue
  - drivers/tty/vt/vt.c:respond_string
```
**Symbols:**

```
ffffffff816807e0-ffffffff8168080d: tty_schedule_flip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void tty_schedule_flip(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8169ae65)
Location: drivers/tty/tty_buffer.c:405
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_flip_buffer_push
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/vt/keyboard.c:k_shift
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:puts_queue
  - drivers/tty/vt/vt.c:respond_string
```
**Symbols:**

```
ffffffff8169ae30-ffffffff8169ae5d: tty_schedule_flip (STB_GLOBAL)
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
