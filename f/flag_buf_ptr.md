# Function: <code>flag_buf_ptr</code>

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
In drivers/tty/tty_buffer.c (ffffffff814eab69)
Location: include/linux/tty.h:78
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
```
```
In drivers/tty/vt/keyboard.c (ffffffff814f2522)
Location: include/linux/tty.h:78
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
Location: include/linux/tty.h:78
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:respond_string
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff814fe444)
Location: include/linux/tty.h:78
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff815019ae)
Location: include/linux/tty.h:78
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff815105b0)
Location: include/linux/tty.h:78
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
In drivers/tty/tty_buffer.c (ffffffff8153baa4)
Location: include/linux/tty.h:78
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
```
```
In drivers/tty/vt/keyboard.c (ffffffff81544669)
Location: include/linux/tty.h:78
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
Location: include/linux/tty.h:78
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:respond_string
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8154ef74)
Location: include/linux/tty.h:78
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff8155235e)
Location: include/linux/tty.h:78
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff81562b20)
Location: include/linux/tty.h:78
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
In drivers/tty/tty_buffer.c (ffffffff81568124)
Location: include/linux/tty.h:78
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
```
```
In drivers/tty/vt/keyboard.c (ffffffff81570ca9)
Location: include/linux/tty.h:78
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
Location: include/linux/tty.h:78
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:respond_string
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8157b7f4)
Location: include/linux/tty.h:78
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff8157ef5e)
Location: include/linux/tty.h:78
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff8158f290)
Location: include/linux/tty.h:78
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
In drivers/tty/tty_buffer.c (ffffffff8157b2f5)
Location: include/linux/tty.h:78
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
```
```
In drivers/tty/vt/keyboard.c (ffffffff81585687)
Location: include/linux/tty.h:78
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_event
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/tty.h:78
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/tty.h:78
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff815936f4)
Location: include/linux/tty.h:78
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (0)
Location: include/linux/tty.h:78
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
In drivers/tty/tty_buffer.c (ffffffff815dfd05)
Location: include/linux/tty.h:79
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
```
```
In drivers/tty/vt/keyboard.c (ffffffff815ea18d)
Location: include/linux/tty.h:79
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_event
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/tty.h:79
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/tty.h:79
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff815f8204)
Location: include/linux/tty.h:79
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (0)
Location: include/linux/tty.h:79
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
In drivers/tty/tty_buffer.c (ffffffff81618f85)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
```
```
In drivers/tty/vt/keyboard.c (ffffffff81623347)
Location: include/linux/tty.h:80
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
In drivers/tty/vt/vt.c (ffffffff81627252)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:respond_string
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8162d172)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff8163107c)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff81642187)
Location: include/linux/tty.h:80
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
In drivers/tty/tty_buffer.c (ffffffff816362f1)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
```
```
In drivers/tty/vt/keyboard.c (ffffffff81640883)
Location: include/linux/tty.h:80
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
In drivers/tty/vt/vt.c (ffffffff81644e02)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:respond_string
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8164b849)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff8164f23c)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff816602e7)
Location: include/linux/tty.h:80
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
In drivers/tty/tty_buffer.c (ffffffff8166a5f6)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
```
```
In drivers/tty/vt/keyboard.c (ffffffff81674f60)
Location: include/linux/tty.h:80
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
In drivers/tty/vt/vt.c (ffffffff81679fa2)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:respond_string
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff816800a9)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff81683f7e)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff81695e87)
Location: include/linux/tty.h:80
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
In drivers/tty/tty_buffer.c (ffffffff8168cce6)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
```
```
In drivers/tty/vt/keyboard.c (ffffffff816976ce)
Location: include/linux/tty.h:80
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
In drivers/tty/vt/vt.c (ffffffff8169c792)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:respond_string
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff816a2759)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff816a662e)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff816b8a17)
Location: include/linux/tty.h:80
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
In drivers/tty/tty_buffer.c (ffffffff8173ed05)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
```
```
In drivers/tty/vt/keyboard.c (ffffffff81749544)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:puts_queue
  - drivers/tty/vt/keyboard.c:put_queue
```
```
In drivers/tty/vt/vt.c (ffffffff8174dbc2)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:respond_string
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81754bf9)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff817582f3)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff8176cd13)
Location: include/linux/tty.h:80
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
In drivers/tty/tty_buffer.c (ffffffff8175ac35)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
```
```
In drivers/tty/vt/keyboard.c (ffffffff81765004)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:put_queue
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8176fef7)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff817733b3)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff817877d1)
Location: include/linux/tty.h:80
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
In drivers/tty/tty_buffer.c (ffffffff8173ead5)
Location: include/linux/tty.h:56
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
```
```
In drivers/tty/vt/keyboard.c (ffffffff81748c34)
Location: include/linux/tty.h:56
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:put_queue
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff817539a9)
Location: include/linux/tty.h:56
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff81756e1c)
Location: include/linux/tty.h:56
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff8176b185)
Location: include/linux/tty.h:56
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
In drivers/tty/tty_buffer.c (ffffffff817bf46e)
Location: include/linux/tty_buffer.h:32
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
```
```
In drivers/tty/vt/keyboard.c (ffffffff817ca094)
Location: include/linux/tty_buffer.h:32
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:put_queue
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff817d6ea2)
Location: include/linux/tty_buffer.h:32
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff817da6fc)
Location: include/linux/tty_buffer.h:32
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff817f0815)
Location: include/linux/tty_buffer.h:32
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
In drivers/tty/tty_buffer.c (ffffffff818fb936)
Location: include/linux/tty_buffer.h:32
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
```
```
In drivers/tty/vt/keyboard.c (ffffffff81907701)
Location: include/linux/tty_buffer.h:32
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:put_queue
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81914fb1)
Location: include/linux/tty_buffer.h:32
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff819194c4)
Location: include/linux/tty_buffer.h:32
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff81930c1c)
Location: include/linux/tty_buffer.h:32
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
In drivers/tty/tty_buffer.c (ffffffff81a54d4b)
Location: include/linux/tty_buffer.h:30
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
```
```
In drivers/tty/vt/keyboard.c (ffffffff81a61d51)
Location: include/linux/tty_buffer.h:30
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:put_queue
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81a70217)
Location: include/linux/tty_buffer.h:30
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff81a752ad)
Location: include/linux/tty_buffer.h:30
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff81a8f22f)
Location: include/linux/tty_buffer.h:30
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
In drivers/tty/tty_buffer.c (ffffffff81a9f21b)
Location: include/linux/tty_buffer.h:30
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
```
```
In drivers/tty/vt/keyboard.c (ffffffff81aac47a)
Location: include/linux/tty_buffer.h:30
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:put_queue
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81aba9d3)
Location: include/linux/tty_buffer.h:30
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff81abfaa6)
Location: include/linux/tty_buffer.h:30
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff81ada9fc)
Location: include/linux/tty_buffer.h:30
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
In drivers/tty/tty_buffer.c (ffffffff81af1cc3)
Location: include/linux/tty_buffer.h:30
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:__tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:__tty_insert_flip_string_flags
```
```
In drivers/tty/vt/keyboard.c (ffffffff81aff048)
Location: include/linux/tty_buffer.h:30
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:put_queue
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81b0d73b)
Location: include/linux/tty_buffer.h:30
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff81b128ed)
Location: include/linux/tty_buffer.h:30
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff81b2dd3f)
Location: include/linux/tty_buffer.h:30
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
In drivers/tty/tty_buffer.c (ffff80001085d784)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
```
```
In drivers/tty/vt/keyboard.c (ffff80001086b874)
Location: include/linux/tty.h:80
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
In drivers/tty/vt/vt.c (ffff8000108731e0)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:respond_string
```
```
In drivers/tty/hvc/hvc_console.c (ffff80001087ac54)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffff80001087deb0)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/imx.c (ffff80001089dd28)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/serial/imx.c:imx_uart_dma_rx_callback
```
```
In drivers/tty/serial/meson_uart.c (ffff80001089f5cc)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/serial/meson_uart.c:meson_uart_interrupt
  - drivers/tty/serial/meson_uart.c:meson_uart_interrupt
```
```
In drivers/tty/serial/msm_serial.c (ffff8000108a42d8)
Location: include/linux/tty.h:80
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
In drivers/tty/serial/mvebu-uart.c (ffff8000108a5514)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars
```
```
In drivers/tty/serial/owl-uart.c (ffff8000108a762c)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
```
```
In drivers/tty/serial/kgdb_nmi.c (ffff8000108a8584)
Location: include/linux/tty.h:80
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
In drivers/tty/tty_buffer.c (c0965220)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
```
```
In drivers/tty/vt/keyboard.c (c0971238)
Location: include/linux/tty.h:80
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
In drivers/tty/vt/vt.c (c0976d94)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:respond_string
```
```
In drivers/tty/hvc/hvc_console.c (c097cab8)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (c097fd88)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/imx.c (c099605c)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/serial/imx.c:imx_uart_dma_rx_callback
```
```
In drivers/tty/serial/meson_uart.c (c0999080)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/serial/meson_uart.c:meson_uart_interrupt
  - drivers/tty/serial/meson_uart.c:meson_uart_interrupt
```
```
In drivers/tty/serial/msm_serial.c (c099d884)
Location: include/linux/tty.h:80
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
In drivers/tty/serial/mvebu-uart.c (c09a24c0)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars
```
```
In drivers/tty/serial/owl-uart.c (c09a307c)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
```
```
In drivers/tty/serial/rda-uart.c (c09a3dbc)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/serial/rda-uart.c:rda_interrupt
```
```
In drivers/tty/serial/kgdb_nmi.c (c09a50b4)
Location: include/linux/tty.h:80
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
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
```
```
In drivers/tty/vt/keyboard.c (c00000000090cf70)
Location: include/linux/tty.h:80
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
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:puts_queue
```
```
In drivers/tty/vt/vt.c (c000000000915180)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:respond_string
```
```
In drivers/tty/hvc/hvsi.c (c00000000091f4c0)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/hvc/hvsi.c:hvsi_insert_chars
```
```
In drivers/tty/hvc/hvc_console.c (c000000000921ce0)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (c000000000926060)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (c00000000093f480)
Location: include/linux/tty.h:80
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
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
```
```
In drivers/tty/vt/keyboard.c (ffffffe00053fe6c)
Location: include/linux/tty.h:80
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
In drivers/tty/vt/vt.c (ffffffe000545abe)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:respond_string
```
```
In drivers/tty/hvc/hvc_console.c (ffffffe00054a9bc)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffe00054ce46)
Location: include/linux/tty.h:80
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
In drivers/tty/tty_buffer.c (ffffffff81652766)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
```
```
In drivers/tty/vt/keyboard.c (ffffffff8165d12e)
Location: include/linux/tty.h:80
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
In drivers/tty/vt/vt.c (ffffffff816621f2)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:respond_string
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff816681b9)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff8166c08e)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff8167e477)
Location: include/linux/tty.h:80
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
In drivers/tty/tty_buffer.c (ffffffff81632ba6)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
```
```
In drivers/tty/vt/keyboard.c (ffffffff8163d4ae)
Location: include/linux/tty.h:80
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
In drivers/tty/vt/vt.c (ffffffff81642572)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:respond_string
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81648539)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff8164b1ee)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff8165d567)
Location: include/linux/tty.h:80
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
In drivers/tty/tty_buffer.c (ffffffff81680b26)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
```
```
In drivers/tty/vt/keyboard.c (ffffffff8168b50e)
Location: include/linux/tty.h:80
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
In drivers/tty/vt/vt.c (ffffffff816905d2)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:respond_string
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81696599)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff8169a46e)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff816ac857)
Location: include/linux/tty.h:80
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
In drivers/tty/tty_buffer.c (ffffffff8169b176)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_prepare_flip_string
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_flags
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_fixed_flag
```
```
In drivers/tty/vt/keyboard.c (ffffffff816a5b0c)
Location: include/linux/tty.h:80
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
In drivers/tty/vt/vt.c (ffffffff816aabc2)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:respond_string
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff816b0b59)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
```
```
In drivers/tty/serial/serial_core.c (ffffffff816b506e)
Location: include/linux/tty.h:80
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff816c6cb7)
Location: include/linux/tty.h:80
Inline: True
```
</details>
</li>
</ul>

## Differences
