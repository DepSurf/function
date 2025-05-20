# Function: <code>scr_writew</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
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
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/console/vgacon.c (c00000000089b6f4)
Location: arch/powerpc/include/asm/vga.h:27
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_invert_region
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/core/fbcon.c (c0000000008aec2c)
Location: arch/powerpc/include/asm/vga.h:27
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_invert_region
  - drivers/video/fbdev/core/fbcon.c:set_vc_hi_font
  - drivers/video/fbdev/core/fbcon.c:set_vc_hi_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_putc
```
```
In drivers/tty/vt/vt.c (c00000000091bea0)
Location: arch/powerpc/include/asm/vga.h:27
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vcs_scr_writew
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:hide_cursor
  - drivers/tty/vt/vt.c:add_softcursor
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:invert_screen
```
</details>
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
