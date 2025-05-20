# Function: <code>redraw_screen</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void redraw_screen(struct vc_data *vc, int is_switch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff814f82d0)
Location: drivers/tty/vt/vt.c:664
Inline: False
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_set_disp
  - drivers/video/console/fbcon.c:fbcon_prepare_logo
  - drivers/video/console/fbcon.c:fbcon_modechanged
  - drivers/video/console/fbcon.c:fbcon_blank
  - drivers/video/console/fbcon.c:fbcon_do_set_font
  - drivers/video/console/fbcon.c:set_con2fb_map
  - drivers/video/console/fbcon.c:fbcon_event_notify
  - drivers/tty/vt/vt_ioctl.c:complete_change_console
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:do_bind_con_driver
```
**Symbols:**

```
ffffffff814f82d0-ffffffff814f8568: redraw_screen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void redraw_screen(struct vc_data *vc, int is_switch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff815489a0)
Location: drivers/tty/vt/vt.c:658
Inline: False
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_event_notify
  - drivers/video/console/fbcon.c:fbcon_modechanged
  - drivers/video/console/fbcon.c:fbcon_do_set_font
  - drivers/video/console/fbcon.c:fbcon_blank
  - drivers/video/console/fbcon.c:fbcon_set_disp
  - drivers/video/console/fbcon.c:set_con2fb_map
  - drivers/video/console/fbcon.c:fbcon_prepare_logo
  - drivers/tty/vt/vt_ioctl.c:complete_change_console
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
ffffffff815489a0-ffffffff81548c00: redraw_screen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void redraw_screen(struct vc_data *vc, int is_switch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81575400)
Location: drivers/tty/vt/vt.c:647
Inline: False
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_event_notify
  - drivers/video/console/fbcon.c:fbcon_modechanged
  - drivers/video/console/fbcon.c:fbcon_do_set_font
  - drivers/video/console/fbcon.c:fbcon_blank
  - drivers/video/console/fbcon.c:fbcon_set_disp
  - drivers/video/console/fbcon.c:set_con2fb_map
  - drivers/video/console/fbcon.c:fbcon_prepare_logo
  - drivers/tty/vt/vt_ioctl.c:complete_change_console
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
ffffffff81575400-ffffffff81575660: redraw_screen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void redraw_screen(struct vc_data *vc, int is_switch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff815892b0)
Location: drivers/tty/vt/vt.c:655
Inline: False
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_event_notify
  - drivers/video/console/fbcon.c:fbcon_modechanged
  - drivers/video/console/fbcon.c:fbcon_do_set_font
  - drivers/video/console/fbcon.c:fbcon_blank
  - drivers/video/console/fbcon.c:fbcon_set_disp
  - drivers/video/console/fbcon.c:set_con2fb_map
  - drivers/video/console/fbcon.c:fbcon_prepare_logo
  - drivers/tty/vt/vt_ioctl.c:complete_change_console
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
ffffffff815892b0-ffffffff815894f8: redraw_screen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void redraw_screen(struct vc_data *vc, int is_switch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff815edde0)
Location: drivers/tty/vt/vt.c:657
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_event_notify
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/tty/vt/vt_ioctl.c:complete_change_console
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
ffffffff815edde0-ffffffff815ee02e: redraw_screen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void redraw_screen(struct vc_data *vc, int is_switch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff816272d0)
Location: drivers/tty/vt/vt.c:657
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_event_notify
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/tty/vt/vt_ioctl.c:complete_change_console
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
ffffffff816272d0-ffffffff81627510: redraw_screen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void redraw_screen(struct vc_data *vc, int is_switch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81644e40)
Location: drivers/tty/vt/vt.c:964
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_event_notify
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/tty/vt/vt_ioctl.c:complete_change_console
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
ffffffff81644e40-ffffffff8164508e: redraw_screen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void redraw_screen(struct vc_data *vc, int is_switch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vt.c (0)
Location: drivers/tty/vt/vt.c:964
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_resumed
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/tty/vt/vt_ioctl.c:complete_change_console
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
ffffffff8167f09b-ffffffff8167f0ae: redraw_screen.cold (STB_LOCAL)
ffffffff81679370-ffffffff816795d0: redraw_screen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void redraw_screen(struct vc_data *vc, int is_switch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8169bb50)
Location: drivers/tty/vt/vt.c:976
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_resumed
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/tty/vt/vt_ioctl.c:complete_change_console
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
ffffffff8169bb50-ffffffff8169bdb2: redraw_screen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void redraw_screen(struct vc_data *vc, int is_switch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8174ed20)
Location: drivers/tty/vt/vt.c:982
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_resumed
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/tty/vt/vt_ioctl.c:complete_change_console
  - drivers/tty/vt/vt.c:do_unblank_screen
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
ffffffff8174ed20-ffffffff8174ef80: redraw_screen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void redraw_screen(struct vc_data *vc, int is_switch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8176a6a0)
Location: drivers/tty/vt/vt.c:988
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_resumed
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/tty/vt/vt_ioctl.c:complete_change_console
  - drivers/tty/vt/vt.c:do_unblank_screen
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
ffffffff8176a6a0-ffffffff8176a902: redraw_screen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void redraw_screen(struct vc_data *vc, int is_switch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8174e270)
Location: drivers/tty/vt/vt.c:988
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_resumed
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/tty/vt/vt_ioctl.c:complete_change_console
  - drivers/tty/vt/vt.c:do_unblank_screen
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
ffffffff8174e270-ffffffff8174e4b9: redraw_screen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void redraw_screen(struct vc_data *vc, int is_switch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff817cf830)
Location: drivers/tty/vt/vt.c:984
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_resumed
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/tty/vt/vt_ioctl.c:complete_change_console
  - drivers/tty/vt/vt.c:do_unblank_screen
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
ffffffff817cf830-ffffffff817cfaca: redraw_screen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void redraw_screen(struct vc_data *vc, int is_switch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8190d6e0)
Location: drivers/tty/vt/vt.c:984
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_resumed
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/tty/vt/vt_ioctl.c:complete_change_console
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
ffffffff8190d6e0-ffffffff8190d98e: redraw_screen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void redraw_screen(struct vc_data *vc, int is_switch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81a683e0)
Location: drivers/tty/vt/vt.c:984
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_resumed
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/tty/vt/vt_ioctl.c:complete_change_console
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
ffffffff81a683e0-ffffffff81a6868e: redraw_screen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void redraw_screen(struct vc_data *vc, int is_switch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81ab2ac0)
Location: drivers/tty/vt/vt.c:933
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_resumed
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/tty/vt/vt_ioctl.c:complete_change_console
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
ffffffff81ab2ac0-ffffffff81ab2d6e: redraw_screen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void redraw_screen(struct vc_data *vc, int is_switch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81b057a0)
Location: drivers/tty/vt/vt.c:932
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_resumed
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/tty/vt/vt_ioctl.c:complete_change_console
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
ffffffff81b057a0-ffffffff81b05a4e: redraw_screen (STB_GLOBAL)
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
void redraw_screen(struct vc_data *vc, int is_switch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffff800010873228)
Location: drivers/tty/vt/vt.c:976
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_resumed
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/tty/vt/vt_ioctl.c:complete_change_console
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
ffff800010873228-ffff8000108734b4: redraw_screen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void redraw_screen(struct vc_data *vc, int is_switch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (c0975f10)
Location: drivers/tty/vt/vt.c:976
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_resumed
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/tty/vt/vt_ioctl.c:complete_change_console
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
c0975f10-c0976194: redraw_screen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void redraw_screen(struct vc_data *vc, int is_switch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (c000000000913d70)
Location: drivers/tty/vt/vt.c:976
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_resumed
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/tty/vt/vt_ioctl.c:complete_change_console
  - drivers/tty/vt/vt.c:do_unblank_screen
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
c000000000913d70-c0000000009140c4: redraw_screen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void redraw_screen(struct vc_data *vc, int is_switch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffe000544c9c)
Location: drivers/tty/vt/vt.c:976
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_resumed
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/tty/vt/vt_ioctl.c:complete_change_console
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
ffffffe000544c9c-ffffffe000544ed0: redraw_screen (STB_GLOBAL)
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
void redraw_screen(struct vc_data *vc, int is_switch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff816615b0)
Location: drivers/tty/vt/vt.c:976
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_resumed
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/tty/vt/vt_ioctl.c:complete_change_console
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
ffffffff816615b0-ffffffff81661812: redraw_screen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void redraw_screen(struct vc_data *vc, int is_switch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81641930)
Location: drivers/tty/vt/vt.c:976
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_resumed
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/tty/vt/vt_ioctl.c:complete_change_console
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
ffffffff81641930-ffffffff81641b92: redraw_screen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void redraw_screen(struct vc_data *vc, int is_switch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8168f990)
Location: drivers/tty/vt/vt.c:976
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_resumed
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/tty/vt/vt_ioctl.c:complete_change_console
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
ffffffff8168f990-ffffffff8168fbf2: redraw_screen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void redraw_screen(struct vc_data *vc, int is_switch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff816a9f90)
Location: drivers/tty/vt/vt.c:976
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_resumed
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/tty/vt/vt_ioctl.c:complete_change_console
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
ffffffff816a9f90-ffffffff816aa1f2: redraw_screen (STB_GLOBAL)
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
