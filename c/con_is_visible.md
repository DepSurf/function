# Function: <code>con_is_visible</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/console/vgacon.c (ffffffff814ac60a)
Location: include/linux/console_struct.h:170
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_deinit
```
```
In drivers/video/console/fbcon.c (ffffffff814b4101)
Location: include/linux/console_struct.h:170
Inline: True
Inline callers:
  - drivers/video/console/fbcon.c:fbcon_event_notify
  - drivers/video/console/fbcon.c:fbcon_set_all_vcs
  - drivers/video/console/fbcon.c:fbcon_modechanged
  - drivers/video/console/fbcon.c:fbcon_set_palette
  - drivers/video/console/fbcon.c:fbcon_do_set_font
  - drivers/video/console/fbcon.c:fbcon_do_set_font
  - drivers/video/console/fbcon.c:fbcon_do_set_font
  - drivers/video/console/fbcon.c:fbcon_resize
  - drivers/video/console/fbcon.c:fbcon_set_disp
  - drivers/video/console/fbcon.c:fbcon_deinit
  - drivers/video/console/fbcon.c:fbcon_init
  - drivers/video/console/fbcon.c:fbcon_prepare_logo
  - drivers/video/console/fbcon.c:fb_flashcursor
```
```
In drivers/tty/vt/vt.c (ffffffff815497aa)
Location: include/linux/console_struct.h:170
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:hide_cursor
  - drivers/tty/vt/vt.c:add_softcursor
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:scrdown
  - drivers/tty/vt/vt.c:scrup
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
In drivers/video/console/vgacon.c (ffffffff814ce6ca)
Location: include/linux/console_struct.h:170
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_deinit
```
```
In drivers/video/console/fbcon.c (ffffffff814d6131)
Location: include/linux/console_struct.h:170
Inline: True
Inline callers:
  - drivers/video/console/fbcon.c:fbcon_event_notify
  - drivers/video/console/fbcon.c:fbcon_set_all_vcs
  - drivers/video/console/fbcon.c:fbcon_modechanged
  - drivers/video/console/fbcon.c:fbcon_set_palette
  - drivers/video/console/fbcon.c:fbcon_do_set_font
  - drivers/video/console/fbcon.c:fbcon_do_set_font
  - drivers/video/console/fbcon.c:fbcon_do_set_font
  - drivers/video/console/fbcon.c:fbcon_resize
  - drivers/video/console/fbcon.c:fbcon_set_disp
  - drivers/video/console/fbcon.c:fbcon_deinit
  - drivers/video/console/fbcon.c:fbcon_init
  - drivers/video/console/fbcon.c:fbcon_prepare_logo
  - drivers/video/console/fbcon.c:fb_flashcursor
```
```
In drivers/tty/vt/vt.c (ffffffff815761da)
Location: include/linux/console_struct.h:170
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:hide_cursor
  - drivers/tty/vt/vt.c:add_softcursor
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:con_scroll
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
In drivers/video/console/vgacon.c (ffffffff814da42a)
Location: include/linux/console_struct.h:170
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_deinit
```
```
In drivers/video/console/fbcon.c (ffffffff814e1263)
Location: include/linux/console_struct.h:170
Inline: True
Inline callers:
  - drivers/video/console/fbcon.c:fbcon_event_notify
  - drivers/video/console/fbcon.c:fbcon_set_all_vcs
  - drivers/video/console/fbcon.c:fbcon_modechanged
  - drivers/video/console/fbcon.c:fbcon_set_palette
  - drivers/video/console/fbcon.c:fbcon_do_set_font
  - drivers/video/console/fbcon.c:fbcon_do_set_font
  - drivers/video/console/fbcon.c:fbcon_do_set_font
  - drivers/video/console/fbcon.c:fbcon_resize
  - drivers/video/console/fbcon.c:fbcon_set_disp
  - drivers/video/console/fbcon.c:fbcon_deinit
  - drivers/video/console/fbcon.c:fbcon_init
  - drivers/video/console/fbcon.c:fbcon_prepare_logo
  - drivers/video/console/fbcon.c:fb_flashcursor
```
```
In drivers/tty/vt/vt.c (ffffffff8158a088)
Location: include/linux/console_struct.h:170
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:hide_cursor
  - drivers/tty/vt/vt.c:add_softcursor
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:con_scroll
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
In drivers/video/console/vgacon.c (ffffffff8151a5ba)
Location: include/linux/console_struct.h:171
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_deinit
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff8152af19)
Location: include/linux/console_struct.h:171
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_event_notify
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_palette
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fb_flashcursor
```
```
In drivers/tty/vt/vt.c (ffffffff815ee62d)
Location: include/linux/console_struct.h:171
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:hide_cursor
  - drivers/tty/vt/vt.c:add_softcursor
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:con_scroll
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
In drivers/video/console/vgacon.c (ffffffff815503b7)
Location: include/linux/console_struct.h:171
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_set_palette
  - drivers/video/console/vgacon.c:vgacon_deinit
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff8155fd23)
Location: include/linux/console_struct.h:171
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_event_notify
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_palette
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fb_flashcursor
```
```
In drivers/tty/vt/vt.c (ffffffff81627acf)
Location: include/linux/console_struct.h:171
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:hide_cursor
  - drivers/tty/vt/vt.c:add_softcursor
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:con_scroll
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
In drivers/video/console/vgacon.c (ffffffff81567707)
Location: include/linux/console_struct.h:171
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_set_palette
  - drivers/video/console/vgacon.c:vgacon_deinit
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff8157833d)
Location: include/linux/console_struct.h:171
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_event_notify
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_palette
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fb_flashcursor
```
```
In drivers/tty/vt/vt.c (ffffffff8164522e)
Location: include/linux/console_struct.h:171
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:hide_cursor
  - drivers/tty/vt/vt.c:add_softcursor
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:update_region
  - drivers/tty/vt/vt.c:con_scroll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
bool con_is_visible(const struct vc_data *vc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vt.c (0)
Location: drivers/tty/vt/vt.c:3875
Inline: False
Direct callers:
  - drivers/video/console/vgacon.c:vgacon_set_palette
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_blanked
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_palette
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fb_flashcursor
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:hide_cursor
  - drivers/tty/vt/vt.c:add_softcursor
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:update_region
  - drivers/tty/vt/vt.c:con_scroll
```
**Symbols:**

```
ffffffff8167f029-ffffffff8167f03c: con_is_visible.cold (STB_LOCAL)
ffffffff81677d70-ffffffff81677daa: con_is_visible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool con_is_visible(const struct vc_data *vc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8169a4f0)
Location: drivers/tty/vt/vt.c:3906
Inline: False
Direct callers:
  - drivers/video/console/vgacon.c:vgacon_set_palette
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_blanked
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_palette
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fb_flashcursor
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:hide_cursor
  - drivers/tty/vt/vt.c:add_softcursor
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:con_scroll
```
**Symbols:**

```
ffffffff8169a4f0-ffffffff8169a536: con_is_visible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool con_is_visible(const struct vc_data *vc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8174cb90)
Location: drivers/tty/vt/vt.c:3916
Inline: False
Direct callers:
  - drivers/video/console/vgacon.c:vgacon_resize
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_set_palette
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_blanked
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_palette
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fb_flashcursor
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:csi_P
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:flush_scrollback
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:hide_cursor
  - drivers/tty/vt/vt.c:add_softcursor
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:update_region
  - drivers/tty/vt/vt.c:con_scroll
```
**Symbols:**

```
ffffffff8174cb90-ffffffff8174cbcb: con_is_visible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool con_is_visible(const struct vc_data *vc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff817681c0)
Location: drivers/tty/vt/vt.c:4005
Inline: False
Direct callers:
  - drivers/video/console/vgacon.c:vgacon_resize
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_set_palette
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_blanked
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_palette
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fb_flashcursor
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vc_con_write_normal
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:csi_P
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:flush_scrollback
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:hide_cursor
  - drivers/tty/vt/vt.c:add_softcursor
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:update_region
  - drivers/tty/vt/vt.c:con_scroll
```
**Symbols:**

```
ffffffff817681c0-ffffffff817681fb: con_is_visible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool con_is_visible(const struct vc_data *vc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8174bde0)
Location: drivers/tty/vt/vt.c:4005
Inline: False
Direct callers:
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_set_palette
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_blanked
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_palette
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fb_flashcursor
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vc_con_write_normal
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:hide_cursor
  - drivers/tty/vt/vt.c:add_softcursor
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:update_region
  - drivers/tty/vt/vt.c:con_scroll
```
**Symbols:**

```
ffffffff8174bde0-ffffffff8174be1b: con_is_visible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool con_is_visible(const struct vc_data *vc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff817d20ae)
Location: drivers/tty/vt/vt.c:4010
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vc_con_write_normal
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:hide_cursor
  - drivers/tty/vt/vt.c:add_softcursor
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:con_scroll
Direct callers:
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_set_palette
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_blanked
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_palette
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fb_flashcursor
```
**Symbols:**

```
ffffffff817cd930-ffffffff817cd96b: con_is_visible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool con_is_visible(const struct vc_data *vc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8190fd08)
Location: drivers/tty/vt/vt.c:4010
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vc_con_write_normal
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:hide_cursor
  - drivers/tty/vt/vt.c:add_softcursor
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:con_scroll
Direct callers:
  - drivers/video/console/vgacon.c:vgacon_resize
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_set_palette
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_blanked
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_palette
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
```
**Symbols:**

```
ffffffff8190b560-ffffffff8190b5a1: con_is_visible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool con_is_visible(const struct vc_data *vc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81a6a4c6)
Location: drivers/tty/vt/vt.c:4009
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vc_con_write_normal
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:hide_cursor
  - drivers/tty/vt/vt.c:add_softcursor
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:con_scroll
Direct callers:
  - drivers/video/console/vgacon.c:vgacon_resize
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_set_palette
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_blanked
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_palette
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
```
**Symbols:**

```
ffffffff81a65e40-ffffffff81a65e81: con_is_visible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool con_is_visible(const struct vc_data *vc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81ab4bb6)
Location: drivers/tty/vt/vt.c:3958
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vc_con_write_normal
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:hide_cursor
  - drivers/tty/vt/vt.c:add_softcursor
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:con_scroll
Direct callers:
  - drivers/video/console/vgacon.c:vgacon_resize
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_set_palette
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_blanked
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_palette
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
```
**Symbols:**

```
ffffffff81ab0530-ffffffff81ab0571: con_is_visible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool con_is_visible(const struct vc_data *vc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81b07896)
Location: drivers/tty/vt/vt.c:3958
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vc_con_write_normal
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:hide_cursor
  - drivers/tty/vt/vt.c:add_softcursor
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:con_scroll
Direct callers:
  - drivers/video/console/vgacon.c:vgacon_resize
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_set_palette
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_blanked
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_palette
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
```
**Symbols:**

```
ffffffff81b031e0-ffffffff81b03221: con_is_visible (STB_GLOBAL)
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
bool con_is_visible(const struct vc_data *vc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffff800010871868)
Location: drivers/tty/vt/vt.c:3906
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_blanked
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_palette
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fb_flashcursor
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:hide_cursor
  - drivers/tty/vt/vt.c:add_softcursor
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:con_scroll
```
**Symbols:**

```
ffff800010871868-ffff8000108718dc: con_is_visible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool con_is_visible(const struct vc_data *vc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (c09747e8)
Location: drivers/tty/vt/vt.c:3906
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_blanked
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_palette
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fb_flashcursor
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:hide_cursor
  - drivers/tty/vt/vt.c:add_softcursor
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:con_scroll
```
**Symbols:**

```
c09747e8-c097485c: con_is_visible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool con_is_visible(const struct vc_data *vc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (c000000000911b50)
Location: drivers/tty/vt/vt.c:3906
Inline: False
Direct callers:
  - drivers/video/console/vgacon.c:vgacon_set_palette
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_blanked
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_palette
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fb_flashcursor
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:hide_cursor
  - drivers/tty/vt/vt.c:add_softcursor
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:update_region
  - drivers/tty/vt/vt.c:con_scroll
```
**Symbols:**

```
c000000000911b50-c000000000911c28: con_is_visible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool con_is_visible(const struct vc_data *vc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffe0005437c4)
Location: drivers/tty/vt/vt.c:3906
Inline: False
Direct callers:
  - drivers/video/console/vgacon.c:vgacon_set_palette
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_blanked
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_palette
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fb_flashcursor
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:hide_cursor
  - drivers/tty/vt/vt.c:add_softcursor
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:con_scroll
```
**Symbols:**

```
ffffffe0005437c4-ffffffe000543814: con_is_visible (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
bool con_is_visible(const struct vc_data *vc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8165ff50)
Location: drivers/tty/vt/vt.c:3906
Inline: False
Direct callers:
  - drivers/video/console/vgacon.c:vgacon_set_palette
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_blanked
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_palette
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fb_flashcursor
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:hide_cursor
  - drivers/tty/vt/vt.c:add_softcursor
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:con_scroll
```
**Symbols:**

```
ffffffff8165ff50-ffffffff8165ff96: con_is_visible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool con_is_visible(const struct vc_data *vc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff816402d0)
Location: drivers/tty/vt/vt.c:3906
Inline: False
Direct callers:
  - drivers/video/console/vgacon.c:vgacon_set_palette
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_blanked
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_palette
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fb_flashcursor
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:hide_cursor
  - drivers/tty/vt/vt.c:add_softcursor
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:con_scroll
```
**Symbols:**

```
ffffffff816402d0-ffffffff81640316: con_is_visible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool con_is_visible(const struct vc_data *vc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8168e330)
Location: drivers/tty/vt/vt.c:3906
Inline: False
Direct callers:
  - drivers/video/console/vgacon.c:vgacon_set_palette
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_blanked
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_palette
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fb_flashcursor
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:hide_cursor
  - drivers/tty/vt/vt.c:add_softcursor
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:con_scroll
```
**Symbols:**

```
ffffffff8168e330-ffffffff8168e376: con_is_visible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool con_is_visible(const struct vc_data *vc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff816a8930)
Location: drivers/tty/vt/vt.c:3906
Inline: False
Direct callers:
  - drivers/video/console/vgacon.c:vgacon_set_palette
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_blanked
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_palette
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fb_flashcursor
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:hide_cursor
  - drivers/tty/vt/vt.c:add_softcursor
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:con_scroll
```
**Symbols:**

```
ffffffff816a8930-ffffffff816a8976: con_is_visible (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
