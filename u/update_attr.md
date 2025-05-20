# Function: <code>update_attr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void update_attr(u8 *dst, u8 *src, int attribute, struct vc_data *vc);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/console/bitblit.c (ffffffff81466350)
Location: drivers/video/console/bitblit.c:25
Inline: True
Direct callers:
  - drivers/video/console/bitblit.c:bit_cursor
  - drivers/video/console/bitblit.c:bit_putcs
  - drivers/video/console/bitblit.c:bit_putcs
```
```
In drivers/tty/vt/vt.c (ffffffff814f77e0)
Location: drivers/tty/vt/vt.c:460
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:restore_cur
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:set_mode
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff81466350-ffffffff814663d7: update_attr.isra.2 (STB_LOCAL)
ffffffff814f77e0-ffffffff814f7895: update_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void update_attr(u8 *dst, u8 *src, int attribute, struct vc_data *vc);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/console/bitblit.c (ffffffff814b4650)
Location: drivers/video/console/bitblit.c:25
Inline: True
Direct callers:
  - drivers/video/console/bitblit.c:bit_cursor
  - drivers/video/console/bitblit.c:bit_putcs
  - drivers/video/console/bitblit.c:bit_putcs
```
```
In drivers/tty/vt/vt.c (ffffffff81548680)
Location: drivers/tty/vt/vt.c:456
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:restore_cur
  - drivers/tty/vt/vt.c:set_mode
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff814b4650-ffffffff814b46dc: update_attr.isra.2 (STB_LOCAL)
ffffffff81548680-ffffffff81548734: update_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void update_attr(u8 *dst, u8 *src, int attribute, struct vc_data *vc);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/console/bitblit.c (ffffffff814d6680)
Location: drivers/video/console/bitblit.c:25
Inline: True
Direct callers:
  - drivers/video/console/bitblit.c:bit_cursor
  - drivers/video/console/bitblit.c:bit_putcs
  - drivers/video/console/bitblit.c:bit_putcs
```
```
In drivers/tty/vt/vt.c (ffffffff81575140)
Location: drivers/tty/vt/vt.c:445
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:restore_cur
  - drivers/tty/vt/vt.c:set_mode
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff814d6680-ffffffff814d670c: update_attr.isra.2 (STB_LOCAL)
ffffffff81575140-ffffffff815751f4: update_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void update_attr(u8 *dst, u8 *src, int attribute, struct vc_data *vc);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/console/bitblit.c (ffffffff814e2360)
Location: drivers/video/console/bitblit.c:25
Inline: True
Direct callers:
  - drivers/video/console/bitblit.c:bit_cursor
  - drivers/video/console/bitblit.c:bit_putcs
  - drivers/video/console/bitblit.c:bit_putcs
```
```
In drivers/tty/vt/vt.c (ffffffff81588f20)
Location: drivers/tty/vt/vt.c:445
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:restore_cur
  - drivers/tty/vt/vt.c:set_mode
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff814e2360-ffffffff814e23ed: update_attr.isra.2 (STB_LOCAL)
ffffffff81588f20-ffffffff81588fca: update_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void update_attr(u8 *dst, u8 *src, int attribute, struct vc_data *vc);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/bitblit.c (ffffffff8152b460)
Location: drivers/video/fbdev/core/bitblit.c:25
Inline: True
Direct callers:
  - drivers/video/fbdev/core/bitblit.c:bit_cursor
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
```
```
In drivers/tty/vt/vt.c (ffffffff815eda30)
Location: drivers/tty/vt/vt.c:447
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:restore_cur
  - drivers/tty/vt/vt.c:set_mode
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff8152b460-ffffffff8152b4ed: update_attr.isra.2 (STB_LOCAL)
ffffffff815eda30-ffffffff815edada: update_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void update_attr(u8 *dst, u8 *src, int attribute, struct vc_data *vc);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/bitblit.c (ffffffff81561030)
Location: drivers/video/fbdev/core/bitblit.c:25
Inline: True
Direct callers:
  - drivers/video/fbdev/core/bitblit.c:bit_cursor
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
```
```
In drivers/tty/vt/vt.c (ffffffff81626e20)
Location: drivers/tty/vt/vt.c:447
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:restore_cur
  - drivers/tty/vt/vt.c:set_mode
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff81561030-ffffffff815610bc: update_attr.isra.1 (STB_LOCAL)
ffffffff81626e20-ffffffff81626eca: update_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void update_attr(u8 *dst, u8 *src, int attribute, struct vc_data *vc);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/bitblit.c (ffffffff81578a30)
Location: drivers/video/fbdev/core/bitblit.c:25
Inline: True
Direct callers:
  - drivers/video/fbdev/core/bitblit.c:bit_cursor
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
```
```
In drivers/tty/vt/vt.c (ffffffff81644480)
Location: drivers/tty/vt/vt.c:749
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:restore_cur
  - drivers/tty/vt/vt.c:set_mode
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff81578a30-ffffffff81578abc: update_attr.isra.1 (STB_LOCAL)
ffffffff81644480-ffffffff8164452a: update_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void update_attr(u8 *dst, u8 *src, int attribute, struct vc_data *vc);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/bitblit.c (ffffffff815a8f80)
Location: drivers/video/fbdev/core/bitblit.c:25
Inline: True
Direct callers:
  - drivers/video/fbdev/core/bitblit.c:bit_cursor
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
```
```
In drivers/tty/vt/vt.c (ffffffff81678c70)
Location: drivers/tty/vt/vt.c:749
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:restore_cur
  - drivers/tty/vt/vt.c:set_mode
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff815a8f80-ffffffff815a900c: update_attr.isra.0 (STB_LOCAL)
ffffffff81678c70-ffffffff81678d1a: update_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void update_attr(u8 *dst, u8 *src, int attribute, struct vc_data *vc);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/bitblit.c (ffffffff815c9f00)
Location: drivers/video/fbdev/core/bitblit.c:25
Inline: True
Direct callers:
  - drivers/video/fbdev/core/bitblit.c:bit_cursor
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
```
```
In drivers/tty/vt/vt.c (ffffffff8169b1f0)
Location: drivers/tty/vt/vt.c:749
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:restore_cur
  - drivers/tty/vt/vt.c:set_mode
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff815c9f00-ffffffff815c9f8c: update_attr.isra.0 (STB_LOCAL)
ffffffff8169b1f0-ffffffff8169b29a: update_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision ⚠️</summary>

```c
void update_attr(u8 *dst, u8 *src, int attribute, struct vc_data *vc);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/bitblit.c (ffffffff816735a0)
Location: drivers/video/fbdev/core/bitblit.c:25
Inline: False
Direct callers:
  - drivers/video/fbdev/core/bitblit.c:bit_cursor
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
```
```
In drivers/tty/vt/vt.c (ffffffff8174c320)
Location: drivers/tty/vt/vt.c:755
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:restore_cur
  - drivers/tty/vt/vt.c:setterm_command
  - drivers/tty/vt/vt.c:set_mode
  - drivers/tty/vt/vt.c:csi_m
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff816735a0-ffffffff8167363a: update_attr (STB_LOCAL)
ffffffff8174c320-ffffffff8174c3ca: update_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
void update_attr(u8 *dst, u8 *src, int attribute, struct vc_data *vc);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/bitblit.c (ffffffff81693730)
Location: drivers/video/fbdev/core/bitblit.c:25
Inline: False
Direct callers:
  - drivers/video/fbdev/core/bitblit.c:bit_cursor
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
```
```
In drivers/tty/vt/vt.c (ffffffff81767a20)
Location: drivers/tty/vt/vt.c:749
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:restore_cur
  - drivers/tty/vt/vt.c:setterm_command
  - drivers/tty/vt/vt.c:set_mode
  - drivers/tty/vt/vt.c:csi_m
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff81693730-ffffffff816937ca: update_attr (STB_LOCAL)
ffffffff81767a20-ffffffff81767abc: update_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision ⚠️</summary>

```c
void update_attr(u8 *dst, u8 *src, int attribute, struct vc_data *vc);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/bitblit.c (ffffffff81676510)
Location: drivers/video/fbdev/core/bitblit.c:25
Inline: False
Direct callers:
  - drivers/video/fbdev/core/bitblit.c:bit_cursor
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
```
```
In drivers/tty/vt/vt.c (ffffffff8174b670)
Location: drivers/tty/vt/vt.c:749
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff81676510-ffffffff816765a9: update_attr (STB_LOCAL)
ffffffff8174b670-ffffffff8174b70c: update_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Transformation ⚠️</summary>

```c
void update_attr(u8 *dst, u8 *src, int attribute, struct vc_data *vc);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/bitblit.c (ffffffff816eb380)
Location: drivers/video/fbdev/core/bitblit.c:25
Inline: False
Direct callers:
  - drivers/video/fbdev/core/bitblit.c:bit_cursor
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
```
```
In drivers/tty/vt/vt.c (0)
Location: drivers/tty/vt/vt.c:745
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff816eb380-ffffffff816eb419: update_attr (STB_LOCAL)
ffffffff817ce380-ffffffff817ce466: update_attr (STB_LOCAL)
ffffffff81cf9583-ffffffff81cf962a: update_attr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Transformation ⚠️</summary>

```c
void update_attr(u8 *dst, u8 *src, int attribute, struct vc_data *vc);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/bitblit.c (ffffffff81816770)
Location: drivers/video/fbdev/core/bitblit.c:25
Inline: False
Direct callers:
  - drivers/video/fbdev/core/bitblit.c:bit_cursor
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
```
```
In drivers/tty/vt/vt.c (0)
Location: drivers/tty/vt/vt.c:745
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff81816770-ffffffff8181683d: update_attr (STB_LOCAL)
ffffffff8190c060-ffffffff8190c15a: update_attr (STB_LOCAL)
ffffffff81ec178b-ffffffff81ec1832: update_attr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Transformation ⚠️</summary>

```c
void update_attr(u8 *dst, u8 *src, int attribute, struct vc_data *vc);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/bitblit.c (ffffffff81945a30)
Location: drivers/video/fbdev/core/bitblit.c:25
Inline: False
Direct callers:
  - drivers/video/fbdev/core/bitblit.c:bit_cursor
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
```
```
In drivers/tty/vt/vt.c (0)
Location: drivers/tty/vt/vt.c:745
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff81945a30-ffffffff81945afd: update_attr (STB_LOCAL)
ffffffff81a669e0-ffffffff81a66ada: update_attr (STB_LOCAL)
ffffffff820959c2-ffffffff82095a69: update_attr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Transformation ⚠️</summary>

```c
void update_attr(u8 *dst, u8 *src, int attribute, struct vc_data *vc);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/bitblit.c (ffffffff8198a070)
Location: drivers/video/fbdev/core/bitblit.c:25
Inline: False
Direct callers:
  - drivers/video/fbdev/core/bitblit.c:bit_cursor
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
```
```
In drivers/tty/vt/vt.c (0)
Location: drivers/tty/vt/vt.c:694
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff8198a070-ffffffff8198a13d: update_attr (STB_LOCAL)
ffffffff81ab11f0-ffffffff81ab12ea: update_attr (STB_LOCAL)
ffffffff82116802-ffffffff821168a9: update_attr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Transformation ⚠️</summary>

```c
void update_attr(struct eventfs_attr *attr, struct iattr *iattr);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/tracefs/event_inode.c (ffffffff816aaf40)
Location: fs/tracefs/event_inode.c:110
Inline: False
Direct callers:
  - fs/tracefs/event_inode.c:eventfs_set_attr
  - fs/tracefs/event_inode.c:eventfs_set_attr
```
```
In drivers/video/fbdev/core/bitblit.c (ffffffff819d3f80)
Location: drivers/video/fbdev/core/bitblit.c:25
Inline: False
Direct callers:
  - drivers/video/fbdev/core/bitblit.c:bit_cursor
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
```
```
In drivers/tty/vt/vt.c (0)
Location: drivers/tty/vt/vt.c:693
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff816aaf40-ffffffff816aaf92: update_attr (STB_LOCAL)
ffffffff819d3f80-ffffffff819d404d: update_attr (STB_LOCAL)
ffffffff81b03e50-ffffffff81b03f4a: update_attr (STB_LOCAL)
ffffffff821f4556-ffffffff821f45fd: update_attr.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void update_attr(u8 *dst, u8 *src, int attribute, struct vc_data *vc);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/bitblit.c (ffff8000107534b0)
Location: drivers/video/fbdev/core/bitblit.c:25
Inline: True
Direct callers:
  - drivers/video/fbdev/core/bitblit.c:bit_cursor
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
```
```
In drivers/tty/vt/vt.c (ffff800010872718)
Location: drivers/tty/vt/vt.c:749
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:restore_cur
  - drivers/tty/vt/vt.c:set_mode
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffff8000107534b0-ffff800010753568: update_attr.isra.0 (STB_LOCAL)
ffff800010872718-ffff8000108727a8: update_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
void update_attr(u8 *dst, u8 *src, int attribute, struct vc_data *vc);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/bitblit.c (c08d59f4)
Location: drivers/video/fbdev/core/bitblit.c:25
Inline: False
Direct callers:
  - drivers/video/fbdev/core/bitblit.c:bit_cursor
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
```
```
In drivers/tty/vt/vt.c (c097563c)
Location: drivers/tty/vt/vt.c:749
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:restore_cur
  - drivers/tty/vt/vt.c:set_mode
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
c08d59f4-c08d5a94: update_attr (STB_LOCAL)
c097563c-c09756dc: update_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision ⚠️</summary>

```c
void update_attr(u8 *dst, u8 *src, int attribute, struct vc_data *vc);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/bitblit.c (c0000000008b7330)
Location: drivers/video/fbdev/core/bitblit.c:25
Inline: False
Direct callers:
  - drivers/video/fbdev/core/bitblit.c:bit_cursor
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
```
```
In drivers/tty/vt/vt.c (c000000000913220)
Location: drivers/tty/vt/vt.c:749
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:restore_cur
  - drivers/tty/vt/vt.c:restore_cur
  - drivers/tty/vt/vt.c:set_mode
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
c0000000008b7330-c0000000008b73e0: update_attr (STB_LOCAL)
c000000000913220-c0000000009132bc: update_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision ⚠️</summary>

```c
void update_attr(u8 *dst, u8 *src, int attribute, struct vc_data *vc);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/bitblit.c (ffffffe00050000e)
Location: drivers/video/fbdev/core/bitblit.c:25
Inline: False
Direct callers:
  - drivers/video/fbdev/core/bitblit.c:bit_cursor
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
```
```
In drivers/tty/vt/vt.c (ffffffe0005444ba)
Location: drivers/tty/vt/vt.c:749
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:restore_cur
  - drivers/tty/vt/vt.c:set_mode
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffe0005444ba-ffffffe000544540: update_attr (STB_LOCAL)
ffffffe00050000e-ffffffe0005000ae: update_attr (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void update_attr(u8 *dst, u8 *src, int attribute, struct vc_data *vc);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/bitblit.c (ffffffff815bdf10)
Location: drivers/video/fbdev/core/bitblit.c:25
Inline: True
Direct callers:
  - drivers/video/fbdev/core/bitblit.c:bit_cursor
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
```
```
In drivers/tty/vt/vt.c (ffffffff81660c50)
Location: drivers/tty/vt/vt.c:749
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:restore_cur
  - drivers/tty/vt/vt.c:set_mode
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff815bdf10-ffffffff815bdf9c: update_attr.isra.0 (STB_LOCAL)
ffffffff81660c50-ffffffff81660cfa: update_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void update_attr(u8 *dst, u8 *src, int attribute, struct vc_data *vc);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/bitblit.c (ffffffff815accf0)
Location: drivers/video/fbdev/core/bitblit.c:25
Inline: True
Direct callers:
  - drivers/video/fbdev/core/bitblit.c:bit_cursor
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
```
```
In drivers/tty/vt/vt.c (ffffffff81640fd0)
Location: drivers/tty/vt/vt.c:749
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:restore_cur
  - drivers/tty/vt/vt.c:set_mode
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff815accf0-ffffffff815acd7c: update_attr.isra.0 (STB_LOCAL)
ffffffff81640fd0-ffffffff8164107a: update_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void update_attr(u8 *dst, u8 *src, int attribute, struct vc_data *vc);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/bitblit.c (ffffffff815be4a0)
Location: drivers/video/fbdev/core/bitblit.c:25
Inline: True
Direct callers:
  - drivers/video/fbdev/core/bitblit.c:bit_cursor
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
```
```
In drivers/tty/vt/vt.c (ffffffff8168f030)
Location: drivers/tty/vt/vt.c:749
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:restore_cur
  - drivers/tty/vt/vt.c:set_mode
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff815be4a0-ffffffff815be52c: update_attr.isra.0 (STB_LOCAL)
ffffffff8168f030-ffffffff8168f0da: update_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void update_attr(u8 *dst, u8 *src, int attribute, struct vc_data *vc);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/bitblit.c (ffffffff815d8040)
Location: drivers/video/fbdev/core/bitblit.c:25
Inline: True
Direct callers:
  - drivers/video/fbdev/core/bitblit.c:bit_cursor
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
```
```
In drivers/tty/vt/vt.c (ffffffff816a9630)
Location: drivers/tty/vt/vt.c:749
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:restore_cur
  - drivers/tty/vt/vt.c:set_mode
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff815d8040-ffffffff815d80cc: update_attr.isra.0 (STB_LOCAL)
ffffffff816a9630-ffffffff816a96da: update_attr (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct eventfs_attr *attr</code>
</li>
<li>
<b>Param added. </b>
<code>struct iattr *iattr</code>
</li>
<li>
<b>Param removed. </b>
<code>u8 *dst</code>
</li>
<li>
<b>Param removed. </b>
<code>u8 *src</code>
</li>
<li>
<b>Param removed. </b>
<code>int attribute</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vc_data *vc</code>
</li>
</ul>
</details>
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
