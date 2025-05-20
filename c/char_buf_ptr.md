# Function: <code>char_buf_ptr</code>

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
In drivers/tty/tty_buffer.c (ffffffff814ea870)
Location: include/linux/tty.h:73
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:flush_to_ldisc
```
```
In drivers/tty/vt/keyboard.c (ffffffff814f2522)
Location: include/linux/tty.h:73
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:puts_queue
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
```
```
In drivers/tty/vt/vt.c (ffffffff814f7ad2)
Location: include/linux/tty.h:73
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:respond_string
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff814fe444)
Location: include/linux/tty.h:73
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff815019ae)
Location: include/linux/tty.h:73
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff815105b0)
Location: include/linux/tty.h:73
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
In drivers/tty/tty_buffer.c (ffffffff8153ba91)
Location: include/linux/tty.h:73
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
```
```
In drivers/tty/vt/keyboard.c (ffffffff81544669)
Location: include/linux/tty.h:73
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
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:puts_queue
```
```
In drivers/tty/vt/vt.c (ffffffff81548912)
Location: include/linux/tty.h:73
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:respond_string
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8154ef74)
Location: include/linux/tty.h:73
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff8155235e)
Location: include/linux/tty.h:73
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff81562b20)
Location: include/linux/tty.h:73
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
In drivers/tty/tty_buffer.c (ffffffff81568111)
Location: include/linux/tty.h:73
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
```
```
In drivers/tty/vt/keyboard.c (ffffffff81570ca9)
Location: include/linux/tty.h:73
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
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:puts_queue
```
```
In drivers/tty/vt/vt.c (ffffffff81575372)
Location: include/linux/tty.h:73
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:respond_string
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8157b7f4)
Location: include/linux/tty.h:73
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff8157ef5e)
Location: include/linux/tty.h:73
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff8158f290)
Location: include/linux/tty.h:73
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
In drivers/tty/tty_buffer.c (ffffffff8157b2e2)
Location: include/linux/tty.h:73
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
```
```
In drivers/tty/vt/keyboard.c (ffffffff81585687)
Location: include/linux/tty.h:73
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_event
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/tty.h:73
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/tty.h:73
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff815936f4)
Location: include/linux/tty.h:73
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (0)
Location: include/linux/tty.h:73
Inline: True
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
In drivers/tty/tty_buffer.c (ffffffff815dfcf2)
Location: include/linux/tty.h:74
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
```
```
In drivers/tty/vt/keyboard.c (ffffffff815ea18d)
Location: include/linux/tty.h:74
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_event
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/tty.h:74
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/tty.h:74
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff815f8204)
Location: include/linux/tty.h:74
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (0)
Location: include/linux/tty.h:74
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
In drivers/tty/tty_buffer.c (ffffffff81618f72)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
```
```
In drivers/tty/vt/keyboard.c (ffffffff8162335c)
Location: include/linux/tty.h:75
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
```
```
In drivers/tty/vt/vt.c (ffffffff8162726a)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:respond_string
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8162d18a)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff8163106d)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff8164219b)
Location: include/linux/tty.h:75
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
In drivers/tty/tty_buffer.c (ffffffff816362de)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
```
```
In drivers/tty/vt/keyboard.c (ffffffff81640883)
Location: include/linux/tty.h:75
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
```
```
In drivers/tty/vt/vt.c (ffffffff81644e1a)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:respond_string
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8164b861)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff8164f22d)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff816602fb)
Location: include/linux/tty.h:75
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
In drivers/tty/tty_buffer.c (ffffffff8166a5e2)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
```
```
In drivers/tty/vt/keyboard.c (ffffffff81674f71)
Location: include/linux/tty.h:75
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
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:puts_queue
```
```
In drivers/tty/vt/vt.c (ffffffff81679fba)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:respond_string
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff816800c1)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff81683f6e)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff81695e9b)
Location: include/linux/tty.h:75
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
In drivers/tty/tty_buffer.c (ffffffff8168ccd2)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
```
```
In drivers/tty/vt/keyboard.c (ffffffff816976df)
Location: include/linux/tty.h:75
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
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:puts_queue
```
```
In drivers/tty/vt/vt.c (ffffffff8169c7aa)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:respond_string
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff816a2771)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff816a661e)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff816b8a2b)
Location: include/linux/tty.h:75
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
In drivers/tty/tty_buffer.c (ffffffff8173ecf2)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
```
```
In drivers/tty/vt/keyboard.c (ffffffff81749544)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:puts_queue
  - drivers/tty/vt/keyboard.c:puts_queue
  - drivers/tty/vt/keyboard.c:put_queue
  - drivers/tty/vt/keyboard.c:put_queue
```
```
In drivers/tty/vt/vt.c (ffffffff8174dbc2)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:respond_string
  - drivers/tty/vt/vt.c:respond_string
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81754bf9)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff817582e2)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff8176cd13)
Location: include/linux/tty.h:75
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
In drivers/tty/tty_buffer.c (ffffffff8175ac22)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
```
```
In drivers/tty/vt/keyboard.c (ffffffff81765004)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:put_queue
  - drivers/tty/vt/keyboard.c:put_queue
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8176fef7)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff817733a2)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff817877d1)
Location: include/linux/tty.h:75
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
In drivers/tty/tty_buffer.c (ffffffff8173eac2)
Location: include/linux/tty.h:51
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
```
```
In drivers/tty/vt/keyboard.c (ffffffff81748c34)
Location: include/linux/tty.h:51
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:put_queue
  - drivers/tty/vt/keyboard.c:put_queue
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff817539a9)
Location: include/linux/tty.h:51
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff81756e0c)
Location: include/linux/tty.h:51
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff8176b185)
Location: include/linux/tty.h:51
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
In drivers/tty/tty_buffer.c (ffffffff817bf45b)
Location: include/linux/tty_buffer.h:27
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
```
```
In drivers/tty/vt/keyboard.c (ffffffff817ca094)
Location: include/linux/tty_buffer.h:27
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:put_queue
  - drivers/tty/vt/keyboard.c:put_queue
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff817d6ea2)
Location: include/linux/tty_buffer.h:27
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff817da6ec)
Location: include/linux/tty_buffer.h:27
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff817f0815)
Location: include/linux/tty_buffer.h:27
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
In drivers/tty/tty_buffer.c (ffffffff818fb926)
Location: include/linux/tty_buffer.h:27
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
```
```
In drivers/tty/vt/keyboard.c (ffffffff81907701)
Location: include/linux/tty_buffer.h:27
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:put_queue
  - drivers/tty/vt/keyboard.c:put_queue
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81914fb1)
Location: include/linux/tty_buffer.h:27
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff819194c4)
Location: include/linux/tty_buffer.h:27
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff81930c1c)
Location: include/linux/tty_buffer.h:27
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_receiver
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
In drivers/tty/tty_buffer.c (ffffffff81a54d30)
Location: include/linux/tty_buffer.h:25
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
```
```
In drivers/tty/vt/keyboard.c (ffffffff81a61d51)
Location: include/linux/tty_buffer.h:25
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:put_queue
  - drivers/tty/vt/keyboard.c:put_queue
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81a70217)
Location: include/linux/tty_buffer.h:25
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff81a752ad)
Location: include/linux/tty_buffer.h:25
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff81a8f22f)
Location: include/linux/tty_buffer.h:25
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_receiver
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
In drivers/tty/tty_buffer.c (ffffffff81a9f200)
Location: include/linux/tty_buffer.h:25
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
```
```
In drivers/tty/vt/keyboard.c (ffffffff81aac47a)
Location: include/linux/tty_buffer.h:25
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:put_queue
  - drivers/tty/vt/keyboard.c:put_queue
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81aba9d3)
Location: include/linux/tty_buffer.h:25
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff81abfaa6)
Location: include/linux/tty_buffer.h:25
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff81ada9fc)
Location: include/linux/tty_buffer.h:25
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_receiver
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
In drivers/tty/tty_buffer.c (ffffffff81af1ca5)
Location: include/linux/tty_buffer.h:25
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:__tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:__tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:__tty_insert_flip_string_flags
```
```
In drivers/tty/vt/keyboard.c (ffffffff81aff048)
Location: include/linux/tty_buffer.h:25
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:put_queue
  - drivers/tty/vt/keyboard.c:put_queue
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81b0d73b)
Location: include/linux/tty_buffer.h:25
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff81b128ed)
Location: include/linux/tty_buffer.h:25
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff81b2dd3f)
Location: include/linux/tty_buffer.h:25
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_receiver
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
In drivers/tty/tty_buffer.c (ffff80001085d768)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
```
```
In drivers/tty/vt/keyboard.c (ffff80001086b88c)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:k_shift
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:puts_queue
```
```
In drivers/tty/vt/vt.c (ffff800010873208)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:respond_string
```
```
In drivers/tty/hvc/hvc_console.c (ffff80001087ac6c)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffff80001087de9c)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/imx.c (ffff80001089dd28)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/serial/imx.c:imx_uart_dma_rx_callback
  - drivers/tty/serial/imx.c:imx_uart_dma_rx_callback
```
```
In drivers/tty/serial/meson_uart.c (ffff80001089f5cc)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/serial/meson_uart.c:meson_uart_interrupt
  - drivers/tty/serial/meson_uart.c:meson_uart_interrupt
  - drivers/tty/serial/meson_uart.c:meson_uart_interrupt
  - drivers/tty/serial/meson_uart.c:meson_uart_interrupt
```
```
In drivers/tty/serial/msm_serial.c (ffff8000108a41cc)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
```
```
In drivers/tty/serial/mvebu-uart.c (ffff8000108a5514)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars
```
```
In drivers/tty/serial/owl-uart.c (ffff8000108a762c)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
```
```
In drivers/tty/serial/kgdb_nmi.c (ffff8000108a859c)
Location: include/linux/tty.h:75
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
In drivers/tty/tty_buffer.c (c096520c)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
```
```
In drivers/tty/vt/keyboard.c (c097124c)
Location: include/linux/tty.h:75
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
  - drivers/tty/vt/keyboard.c:k_shift
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:puts_queue
```
```
In drivers/tty/vt/vt.c (c0976db4)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:respond_string
```
```
In drivers/tty/hvc/hvc_console.c (c097cad0)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (c097fd88)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/imx.c (c099605c)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/serial/imx.c:imx_uart_dma_rx_callback
  - drivers/tty/serial/imx.c:imx_uart_dma_rx_callback
```
```
In drivers/tty/serial/meson_uart.c (c0998fc0)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/serial/meson_uart.c:meson_uart_interrupt
  - drivers/tty/serial/meson_uart.c:meson_uart_interrupt
  - drivers/tty/serial/meson_uart.c:meson_uart_interrupt
  - drivers/tty/serial/meson_uart.c:meson_uart_interrupt
```
```
In drivers/tty/serial/msm_serial.c (c099d63c)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
```
```
In drivers/tty/serial/mvebu-uart.c (c09a24c0)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars
```
```
In drivers/tty/serial/owl-uart.c (c09a2ef0)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
```
```
In drivers/tty/serial/rda-uart.c (c09a3dbc)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/serial/rda-uart.c:rda_interrupt
  - drivers/tty/serial/rda-uart.c:rda_interrupt
```
```
In drivers/tty/serial/kgdb_nmi.c (c09a50c8)
Location: include/linux/tty.h:75
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
In drivers/tty/tty_buffer.c (c0000000008fc6f0)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
```
```
In drivers/tty/vt/keyboard.c (c00000000090cf84)
Location: include/linux/tty.h:75
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
  - drivers/tty/vt/keyboard.c:k_shift
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:puts_queue
```
```
In drivers/tty/vt/vt.c (c0000000009151a4)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:respond_string
```
```
In drivers/tty/hvc/hvsi.c (c00000000091f4e4)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/hvc/hvsi.c:hvsi_insert_chars
```
```
In drivers/tty/hvc/hvc_console.c (c000000000921cf8)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (c000000000926024)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (c00000000093f494)
Location: include/linux/tty.h:75
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
In drivers/tty/tty_buffer.c (ffffffe0005364b8)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
```
```
In drivers/tty/vt/keyboard.c (ffffffe00053fe7c)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:k_shift
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:puts_queue
```
```
In drivers/tty/vt/vt.c (ffffffe000545ad8)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:respond_string
```
```
In drivers/tty/hvc/hvc_console.c (ffffffe00054a9ce)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffe00054ce34)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
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
In drivers/tty/tty_buffer.c (ffffffff81652752)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
```
```
In drivers/tty/vt/keyboard.c (ffffffff8165d13f)
Location: include/linux/tty.h:75
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
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:puts_queue
```
```
In drivers/tty/vt/vt.c (ffffffff8166220a)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:respond_string
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff816681d1)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff8166c07e)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff8167e48b)
Location: include/linux/tty.h:75
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
In drivers/tty/tty_buffer.c (ffffffff81632b92)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
```
```
In drivers/tty/vt/keyboard.c (ffffffff8163d4bf)
Location: include/linux/tty.h:75
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
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:puts_queue
```
```
In drivers/tty/vt/vt.c (ffffffff8164258a)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:respond_string
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81648551)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff8164b1de)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff8165d57b)
Location: include/linux/tty.h:75
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
In drivers/tty/tty_buffer.c (ffffffff81680b12)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
```
```
In drivers/tty/vt/keyboard.c (ffffffff8168b51f)
Location: include/linux/tty.h:75
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
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:puts_queue
```
```
In drivers/tty/vt/vt.c (ffffffff816905ea)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:respond_string
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff816965b1)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff8169a45e)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff816ac86b)
Location: include/linux/tty.h:75
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
In drivers/tty/tty_buffer.c (ffffffff8169b162)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
```
```
In drivers/tty/vt/keyboard.c (ffffffff816a5b1d)
Location: include/linux/tty.h:75
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
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:puts_queue
```
```
In drivers/tty/vt/vt.c (ffffffff816aabda)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:respond_string
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff816b0b71)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff816b505e)
Location: include/linux/tty.h:75
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff816c6ccb)
Location: include/linux/tty.h:75
Inline: True
```
</details>
</li>
</ul>

## Differences
