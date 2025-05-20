# Function: <code>tty_insert_flip_char</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffff814f251e)
Location: include/linux/tty_flip.h:16
Inline: True
Inline callers:
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
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
```
```
In drivers/tty/vt/vt.c (ffffffff814f7ace)
Location: include/linux/tty_flip.h:16
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:respond_string
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff814fe421)
Location: include/linux/tty_flip.h:16
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff815018ed)
Location: include/linux/tty_flip.h:16
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff8151058d)
Location: include/linux/tty_flip.h:16
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_receiver
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffff81544646)
Location: include/linux/tty_flip.h:16
Inline: True
Inline callers:
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
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:k_shift
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:puts_queue
```
```
In drivers/tty/vt/vt.c (ffffffff8154890e)
Location: include/linux/tty_flip.h:16
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:respond_string
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8154ef51)
Location: include/linux/tty_flip.h:16
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff8155229d)
Location: include/linux/tty_flip.h:16
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff81562afd)
Location: include/linux/tty_flip.h:16
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_receiver
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffff81570c86)
Location: include/linux/tty_flip.h:16
Inline: True
Inline callers:
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
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:k_shift
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:puts_queue
```
```
In drivers/tty/vt/vt.c (ffffffff8157536e)
Location: include/linux/tty_flip.h:16
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:respond_string
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8157b7d1)
Location: include/linux/tty_flip.h:16
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff8157ee9d)
Location: include/linux/tty_flip.h:16
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff8158f26d)
Location: include/linux/tty_flip.h:16
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_receiver
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffff81584eba)
Location: include/linux/tty_flip.h:17
Inline: True
Inline callers:
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
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:k_shift
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:puts_queue
```
```
In drivers/tty/vt/vt.c (ffffffff8158923c)
Location: include/linux/tty_flip.h:17
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:respond_string
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8158f725)
Location: include/linux/tty_flip.h:17
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff81593631)
Location: include/linux/tty_flip.h:17
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff815a333d)
Location: include/linux/tty_flip.h:17
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_receiver
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffff815e99ba)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
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
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:k_shift
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:puts_queue
```
```
In drivers/tty/vt/vt.c (ffffffff815edd6c)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:respond_string
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff815f422b)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff815f8141)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff81608a68)
Location: include/linux/tty_flip.h:18
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffff81622bea)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
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
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:k_shift
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:puts_queue
```
```
In drivers/tty/vt/vt.c (ffffffff81627232)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:respond_string
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8162d153)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff81630fa1)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff81642163)
Location: include/linux/tty_flip.h:18
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffff816402f0)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
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
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:k_shift
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:puts_queue
```
```
In drivers/tty/vt/vt.c (ffffffff81644de2)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:respond_string
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8164b82a)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff8164f161)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff816602c3)
Location: include/linux/tty_flip.h:18
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffff81674e95)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
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
```
```
In drivers/tty/vt/vt.c (ffffffff81679f82)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:respond_string
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8168008a)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff81683ea1)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff81695e63)
Location: include/linux/tty_flip.h:18
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffff81697684)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
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
```
```
In drivers/tty/vt/vt.c (ffffffff8169c772)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:respond_string
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff816a273a)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff816a6551)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff816b89f3)
Location: include/linux/tty_flip.h:18
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffff81749505)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:puts_queue
  - drivers/tty/vt/keyboard.c:put_queue
```
```
In drivers/tty/vt/vt.c (ffffffff8174dba2)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:respond_string
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81754bda)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff81758214)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff8176ccef)
Location: include/linux/tty_flip.h:18
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffff81764fc5)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:put_queue
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8176feda)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff817732d4)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff817877af)
Location: include/linux/tty_flip.h:18
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffff81748bf5)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:put_queue
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8175398a)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff81756d3f)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff8176b161)
Location: include/linux/tty_flip.h:18
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffff817ca055)
Location: include/linux/tty_flip.h:23
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:put_queue
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff817d6e8a)
Location: include/linux/tty_flip.h:23
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff817da61f)
Location: include/linux/tty_flip.h:23
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff817f07f1)
Location: include/linux/tty_flip.h:23
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffff819076b5)
Location: include/linux/tty_flip.h:22
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:put_queue
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81914f99)
Location: include/linux/tty_flip.h:22
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff819193d4)
Location: include/linux/tty_flip.h:22
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff81930bf8)
Location: include/linux/tty_flip.h:22
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_receiver
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffff81a61cd5)
Location: include/linux/tty_flip.h:22
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:put_queue
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81a701f1)
Location: include/linux/tty_flip.h:22
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff81a751a1)
Location: include/linux/tty_flip.h:22
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff81a8f1fe)
Location: include/linux/tty_flip.h:22
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_receiver
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffff81aac405)
Location: include/linux/tty_flip.h:22
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:put_queue
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81aba9b1)
Location: include/linux/tty_flip.h:22
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff81abf9a1)
Location: include/linux/tty_flip.h:22
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff81ada9cc)
Location: include/linux/tty_flip.h:22
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_receiver
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffff81afefd9)
Location: include/linux/tty_flip.h:65
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:put_queue
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81b0d716)
Location: include/linux/tty_flip.h:65
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff81b12809)
Location: include/linux/tty_flip.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff81b2dd0d)
Location: include/linux/tty_flip.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_receiver
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffff80001086b7b8)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:k_shift
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:puts_queue
```
```
In drivers/tty/vt/vt.c (ffff8000108731c4)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:respond_string
```
```
In drivers/tty/hvc/hvc_console.c (ffff80001087ac34)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffff80001087ddd4)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/imx.c (ffff80001089dc9c)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/serial/imx.c:imx_uart_dma_rx_callback
```
```
In drivers/tty/serial/meson_uart.c (ffff80001089f450)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/serial/meson_uart.c:meson_uart_interrupt
  - drivers/tty/serial/meson_uart.c:meson_uart_interrupt
```
```
In drivers/tty/serial/msm_serial.c (ffff8000108a41a8)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
```
```
In drivers/tty/serial/mvebu-uart.c (ffff8000108a5430)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars
```
```
In drivers/tty/serial/owl-uart.c (ffff8000108a7594)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
```
```
In drivers/tty/serial/kgdb_nmi.c (ffff8000108a853c)
Location: include/linux/tty_flip.h:18
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (c09711fc)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
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
```
```
In drivers/tty/vt/vt.c (c0976d7c)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:respond_string
```
```
In drivers/tty/hvc/hvc_console.c (c097ca98)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (c097fd68)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/imx.c (c0995fb0)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/serial/imx.c:imx_uart_dma_rx_callback
```
```
In drivers/tty/serial/meson_uart.c (c0998f88)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/serial/meson_uart.c:meson_uart_interrupt
  - drivers/tty/serial/meson_uart.c:meson_uart_interrupt
```
```
In drivers/tty/serial/msm_serial.c (c099d60c)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
```
```
In drivers/tty/serial/mvebu-uart.c (c09a234c)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars
```
```
In drivers/tty/serial/owl-uart.c (c09a2ec0)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
```
```
In drivers/tty/serial/rda-uart.c (c09a3e48)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/serial/rda-uart.c:rda_interrupt
```
```
In drivers/tty/serial/kgdb_nmi.c (c09a5088)
Location: include/linux/tty_flip.h:18
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (c00000000090ce64)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
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
```
```
In drivers/tty/vt/vt.c (c000000000915164)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:respond_string
```
```
In drivers/tty/hvc/hvsi.c (c00000000091f45c)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/hvc/hvsi.c:hvsi_insert_chars
```
```
In drivers/tty/hvc/hvc_console.c (c000000000921cbc)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (c000000000925efc)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (c00000000093f41c)
Location: include/linux/tty_flip.h:18
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffe00053fdd4)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:k_shift
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:puts_queue
```
```
In drivers/tty/vt/vt.c (ffffffe000545a9e)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:respond_string
```
```
In drivers/tty/hvc/hvc_console.c (ffffffe00054a97a)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffe00054cd94)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffff8165d0e4)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
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
```
```
In drivers/tty/vt/vt.c (ffffffff816621d2)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:respond_string
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8166819a)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff8166bfb1)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff8167e453)
Location: include/linux/tty_flip.h:18
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffff8163d464)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
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
```
```
In drivers/tty/vt/vt.c (ffffffff81642552)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:respond_string
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8164851a)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff8164b111)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff8165d543)
Location: include/linux/tty_flip.h:18
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffff8168b4c4)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
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
```
```
In drivers/tty/vt/vt.c (ffffffff816905b2)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:respond_string
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8169657a)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff8169a391)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff816ac833)
Location: include/linux/tty_flip.h:18
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffff816a5ac2)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
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
```
```
In drivers/tty/vt/vt.c (ffffffff816aaba2)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:respond_string
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff816b0b3a)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff816b4f91)
Location: include/linux/tty_flip.h:18
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff816c6c93)
Location: include/linux/tty_flip.h:18
Inline: True
```
</details>
</li>
</ul>

## Differences
