# Function: <code>set_leds</code>

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
In drivers/tty/vt/keyboard.c (ffffffff814f4690)
Location: include/linux/kbd_kern.h:77
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:setledstate
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
```
```
In drivers/tty/vt/vt.c (ffffffff814f83e0)
Location: include/linux/kbd_kern.h:77
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
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
In drivers/tty/vt/keyboard.c (ffffffff81546277)
Location: include/linux/kbd_kern.h:77
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
```
```
In drivers/tty/vt/vt.c (ffffffff81548a85)
Location: include/linux/kbd_kern.h:77
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
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
In drivers/tty/vt/keyboard.c (ffffffff815728c7)
Location: include/linux/kbd_kern.h:77
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
```
```
In drivers/tty/vt/vt.c (ffffffff815754e5)
Location: include/linux/kbd_kern.h:77
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
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
In drivers/tty/vt/keyboard.c (ffffffff8158697a)
Location: include/linux/kbd_kern.h:77
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
```
```
In drivers/tty/vt/vt.c (ffffffff81589399)
Location: include/linux/kbd_kern.h:77
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
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
In drivers/tty/vt/keyboard.c (ffffffff815eb47a)
Location: include/linux/kbd_kern.h:78
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
```
```
In drivers/tty/vt/vt.c (ffffffff815edec9)
Location: include/linux/kbd_kern.h:78
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
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
In drivers/tty/vt/keyboard.c (ffffffff816246a9)
Location: include/linux/kbd_kern.h:78
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
```
```
In drivers/tty/vt/vt.c (ffffffff816273b1)
Location: include/linux/kbd_kern.h:78
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
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
In drivers/tty/vt/keyboard.c (ffffffff81641b99)
Location: include/linux/kbd_kern.h:78
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
```
```
In drivers/tty/vt/vt.c (ffffffff81644f20)
Location: include/linux/kbd_kern.h:78
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
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
In drivers/tty/vt/keyboard.c (ffffffff816760f8)
Location: include/linux/kbd_kern.h:78
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
```
```
In drivers/tty/vt/vt.c (ffffffff81679521)
Location: include/linux/kbd_kern.h:78
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
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
In drivers/tty/vt/keyboard.c (ffffffff81698898)
Location: include/linux/kbd_kern.h:78
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
```
```
In drivers/tty/vt/vt.c (ffffffff8169bd01)
Location: include/linux/kbd_kern.h:78
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
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
In drivers/tty/vt/keyboard.c (ffffffff8174ac08)
Location: include/linux/kbd_kern.h:78
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:vt_set_led_state
```
```
In drivers/tty/vt/vt.c (ffffffff8174eecf)
Location: include/linux/kbd_kern.h:78
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
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
In drivers/tty/vt/keyboard.c (ffffffff81766378)
Location: include/linux/kbd_kern.h:75
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:vt_set_led_state
```
```
In drivers/tty/vt/vt.c (ffffffff8176a851)
Location: include/linux/kbd_kern.h:75
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
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
In drivers/tty/vt/keyboard.c (ffffffff81749fc6)
Location: drivers/tty/vt/keyboard.c:379
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:vt_set_led_state
  - drivers/tty/vt/keyboard.c:vt_set_leds_compute_shiftstate
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
In drivers/tty/vt/keyboard.c (ffffffff817cb621)
Location: drivers/tty/vt/keyboard.c:379
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:vt_set_led_state
  - drivers/tty/vt/keyboard.c:vt_set_leds_compute_shiftstate
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
In drivers/tty/vt/keyboard.c (ffffffff81908e55)
Location: drivers/tty/vt/keyboard.c:380
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:vt_set_led_state
  - drivers/tty/vt/keyboard.c:vt_set_leds_compute_shiftstate
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffff81a63445)
Location: drivers/tty/vt/keyboard.c:380
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:vt_set_led_state
  - drivers/tty/vt/keyboard.c:vt_set_leds_compute_shiftstate
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffff81aadb05)
Location: drivers/tty/vt/keyboard.c:380
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:vt_set_led_state
  - drivers/tty/vt/keyboard.c:vt_set_leds_compute_shiftstate
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffff81b00735)
Location: drivers/tty/vt/keyboard.c:380
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:vt_set_led_state
  - drivers/tty/vt/keyboard.c:vt_set_leds_compute_shiftstate
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
In drivers/tty/vt/keyboard.c (ffff80001086e8c8)
Location: include/linux/kbd_kern.h:78
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
```
```
In drivers/tty/vt/vt.c (ffff8000108732fc)
Location: include/linux/kbd_kern.h:78
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
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
In drivers/tty/vt/keyboard.c (c09727f8)
Location: include/linux/kbd_kern.h:78
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
```
```
In drivers/tty/vt/vt.c (c09760c8)
Location: include/linux/kbd_kern.h:78
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
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
In drivers/tty/vt/keyboard.c (c00000000090ee40)
Location: include/linux/kbd_kern.h:78
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
```
```
In drivers/tty/vt/vt.c (c000000000913e88)
Location: include/linux/kbd_kern.h:78
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
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
In drivers/tty/vt/keyboard.c (ffffffe00054199a)
Location: include/linux/kbd_kern.h:78
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
```
```
In drivers/tty/vt/vt.c (ffffffe000544e36)
Location: include/linux/kbd_kern.h:78
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
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
In drivers/tty/vt/keyboard.c (ffffffff8165e2f8)
Location: include/linux/kbd_kern.h:78
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
```
```
In drivers/tty/vt/vt.c (ffffffff81661761)
Location: include/linux/kbd_kern.h:78
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
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
In drivers/tty/vt/keyboard.c (ffffffff8163e678)
Location: include/linux/kbd_kern.h:78
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
```
```
In drivers/tty/vt/vt.c (ffffffff81641ae1)
Location: include/linux/kbd_kern.h:78
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
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
In drivers/tty/vt/keyboard.c (ffffffff8168c6d8)
Location: include/linux/kbd_kern.h:78
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
```
```
In drivers/tty/vt/vt.c (ffffffff8168fb41)
Location: include/linux/kbd_kern.h:78
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
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
In drivers/tty/vt/keyboard.c (ffffffff816a6cd8)
Location: include/linux/kbd_kern.h:78
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
```
```
In drivers/tty/vt/vt.c (ffffffff816aa141)
Location: include/linux/kbd_kern.h:78
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
```
</details>
</li>
</ul>

## Differences
