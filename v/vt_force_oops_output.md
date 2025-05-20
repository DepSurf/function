# Function: <code>vt_force_oops_output</code>

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
In drivers/video/console/fbcon.c (ffffffff8145f85c)
Location: include/linux/vt_kern.h:139
Inline: True
Inline callers:
  - drivers/video/console/fbcon.c:fbcon_clear_margins
  - drivers/video/console/fbcon.c:fbcon_clear
  - drivers/video/console/fbcon.c:fbcon_bmove
  - drivers/video/console/fbcon.c:fbcon_putcs
  - drivers/video/console/fbcon.c:fbcon_set_palette
  - drivers/video/console/fbcon.c:fbcon_modechanged
  - drivers/video/console/fbcon.c:fbcon_scrolldelta
  - drivers/video/console/fbcon.c:fbcon_cursor
  - drivers/video/console/fbcon.c:fbcon_blank
  - drivers/video/console/fbcon.c:fbcon_blank
  - drivers/video/console/fbcon.c:fbcon_switch
  - drivers/video/console/fbcon.c:fbcon_switch
  - drivers/video/console/fbcon.c:fbcon_scroll
```
```
In drivers/tty/vt/vt.c (ffffffff814f7fc8)
Location: include/linux/vt_kern.h:139
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
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
In drivers/video/console/fbcon.c (ffffffff814af8a1)
Location: include/linux/vt_kern.h:138
Inline: True
Inline callers:
  - drivers/video/console/fbcon.c:fbcon_modechanged
  - drivers/video/console/fbcon.c:fbcon_scrolldelta
  - drivers/video/console/fbcon.c:fbcon_set_palette
  - drivers/video/console/fbcon.c:fbcon_blank
  - drivers/video/console/fbcon.c:fbcon_blank
  - drivers/video/console/fbcon.c:fbcon_switch
  - drivers/video/console/fbcon.c:fbcon_switch
  - drivers/video/console/fbcon.c:fbcon_scroll
  - drivers/video/console/fbcon.c:fbcon_cursor
  - drivers/video/console/fbcon.c:fbcon_clear_margins
  - drivers/video/console/fbcon.c:fbcon_putcs
  - drivers/video/console/fbcon.c:fbcon_clear
```
```
In drivers/tty/vt/vt.c (ffffffff8154a57f)
Location: include/linux/vt_kern.h:138
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
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
In drivers/video/console/fbcon.c (ffffffff814d19b1)
Location: include/linux/vt_kern.h:138
Inline: True
Inline callers:
  - drivers/video/console/fbcon.c:fbcon_modechanged
  - drivers/video/console/fbcon.c:fbcon_scrolldelta
  - drivers/video/console/fbcon.c:fbcon_set_palette
  - drivers/video/console/fbcon.c:fbcon_blank
  - drivers/video/console/fbcon.c:fbcon_blank
  - drivers/video/console/fbcon.c:fbcon_switch
  - drivers/video/console/fbcon.c:fbcon_switch
  - drivers/video/console/fbcon.c:fbcon_scroll
  - drivers/video/console/fbcon.c:fbcon_cursor
  - drivers/video/console/fbcon.c:fbcon_clear_margins
  - drivers/video/console/fbcon.c:fbcon_putcs
  - drivers/video/console/fbcon.c:fbcon_clear
```
```
In drivers/tty/vt/vt.c (ffffffff81576daf)
Location: include/linux/vt_kern.h:138
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
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
In drivers/video/console/fbcon.c (ffffffff814deec5)
Location: include/linux/vt_kern.h:138
Inline: True
Inline callers:
  - drivers/video/console/fbcon.c:fbcon_modechanged
  - drivers/video/console/fbcon.c:fbcon_modechanged
  - drivers/video/console/fbcon.c:fbcon_scrolldelta
  - drivers/video/console/fbcon.c:fbcon_scrolldelta
  - drivers/video/console/fbcon.c:fbcon_set_palette
  - drivers/video/console/fbcon.c:fbcon_set_palette
  - drivers/video/console/fbcon.c:fbcon_blank
  - drivers/video/console/fbcon.c:fbcon_blank
  - drivers/video/console/fbcon.c:fbcon_blank
  - drivers/video/console/fbcon.c:fbcon_blank
  - drivers/video/console/fbcon.c:fbcon_switch
  - drivers/video/console/fbcon.c:fbcon_switch
  - drivers/video/console/fbcon.c:fbcon_switch
  - drivers/video/console/fbcon.c:fbcon_switch
  - drivers/video/console/fbcon.c:fbcon_scroll
  - drivers/video/console/fbcon.c:fbcon_scroll
  - drivers/video/console/fbcon.c:fbcon_cursor
  - drivers/video/console/fbcon.c:fbcon_cursor
  - drivers/video/console/fbcon.c:fbcon_clear_margins
  - drivers/video/console/fbcon.c:fbcon_clear_margins
  - drivers/video/console/fbcon.c:fbcon_putcs
  - drivers/video/console/fbcon.c:fbcon_putcs
  - drivers/video/console/fbcon.c:fbcon_clear
  - drivers/video/console/fbcon.c:fbcon_clear
```
```
In drivers/tty/vt/vt.c (ffffffff8158ae50)
Location: include/linux/vt_kern.h:138
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
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
In drivers/video/fbdev/core/fbcon.c (ffffffff815271f5)
Location: include/linux/vt_kern.h:139
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_palette
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_palette
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_clear_margins
  - drivers/video/fbdev/core/fbcon.c:fbcon_clear_margins
  - drivers/video/fbdev/core/fbcon.c:fbcon_putcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_putcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_clear
  - drivers/video/fbdev/core/fbcon.c:fbcon_clear
```
```
In drivers/tty/vt/vt.c (ffffffff815ef8e5)
Location: include/linux/vt_kern.h:139
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
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
In drivers/video/fbdev/core/fbcon.c (ffffffff8155ceee)
Location: include/linux/vt_kern.h:139
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_palette
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_palette
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_clear_margins
  - drivers/video/fbdev/core/fbcon.c:fbcon_clear_margins
  - drivers/video/fbdev/core/fbcon.c:fbcon_putcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_putcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_clear
  - drivers/video/fbdev/core/fbcon.c:fbcon_clear
```
```
In drivers/tty/vt/vt.c (ffffffff8162850b)
Location: include/linux/vt_kern.h:139
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:redraw_screen
```
</details>
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
