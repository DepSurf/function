# Function: <code>vc_cons_allocated</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int vc_cons_allocated(unsigned int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff814f72ed)
Location: drivers/tty/vt/vt.c:738
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_start
  - drivers/tty/vt/vt.c:con_stop
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:set_console
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:con_font_op
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/keyboard.c:fn_inc_console
  - drivers/tty/vt/keyboard.c:fn_inc_console
  - drivers/tty/vt/keyboard.c:fn_dec_console
  - drivers/tty/vt/keyboard.c:fn_dec_console
  - drivers/tty/vt/consolemap.c:update_user_maps
  - drivers/tty/vt/consolemap.c:console_map_init
```
**Symbols:**

```
ffffffff814fa110-ffffffff814fa137: vc_cons_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int vc_cons_allocated(unsigned int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8154da42)
Location: drivers/tty/vt/vt.c:732
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:con_start
  - drivers/tty/vt/vt.c:con_stop
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:set_console
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:vc_deallocate
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/keyboard.c:fn_inc_console
  - drivers/tty/vt/keyboard.c:fn_inc_console
  - drivers/tty/vt/keyboard.c:fn_dec_console
  - drivers/tty/vt/keyboard.c:fn_dec_console
  - drivers/tty/vt/consolemap.c:console_map_init
  - drivers/tty/vt/consolemap.c:update_user_maps
```
**Symbols:**

```
ffffffff8154ad30-ffffffff8154ad57: vc_cons_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int vc_cons_allocated(unsigned int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8157a2c2)
Location: drivers/tty/vt/vt.c:721
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:con_start
  - drivers/tty/vt/vt.c:con_stop
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:set_console
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:vc_deallocate
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/keyboard.c:fn_inc_console
  - drivers/tty/vt/keyboard.c:fn_inc_console
  - drivers/tty/vt/keyboard.c:fn_dec_console
  - drivers/tty/vt/keyboard.c:fn_dec_console
  - drivers/tty/vt/consolemap.c:console_map_init
  - drivers/tty/vt/consolemap.c:update_user_maps
```
**Symbols:**

```
ffffffff81577560-ffffffff81577587: vc_cons_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int vc_cons_allocated(unsigned int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8158e0d4)
Location: drivers/tty/vt/vt.c:729
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:con_start
  - drivers/tty/vt/vt.c:con_stop
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:set_console
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:vc_deallocate
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/keyboard.c:fn_inc_console
  - drivers/tty/vt/keyboard.c:fn_dec_console
  - drivers/tty/vt/consolemap.c:console_map_init
  - drivers/tty/vt/consolemap.c:update_user_maps
```
**Symbols:**

```
ffffffff8158b460-ffffffff8158b487: vc_cons_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int vc_cons_allocated(unsigned int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff815f2b92)
Location: drivers/tty/vt/vt.c:731
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:con_start
  - drivers/tty/vt/vt.c:con_stop
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:set_console
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:vc_deallocate
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/keyboard.c:fn_inc_console
  - drivers/tty/vt/keyboard.c:fn_dec_console
  - drivers/tty/vt/consolemap.c:console_map_init
  - drivers/tty/vt/consolemap.c:update_user_maps
```
**Symbols:**

```
ffffffff815eff00-ffffffff815eff27: vc_cons_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int vc_cons_allocated(unsigned int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8162bfd5)
Location: drivers/tty/vt/vt.c:731
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:con_start
  - drivers/tty/vt/vt.c:con_stop
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:vc_deallocate
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/keyboard.c:fn_inc_console
  - drivers/tty/vt/keyboard.c:fn_dec_console
  - drivers/tty/vt/consolemap.c:console_map_init
  - drivers/tty/vt/consolemap.c:update_user_maps
```
**Symbols:**

```
ffffffff816293f0-ffffffff81629417: vc_cons_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int vc_cons_allocated(unsigned int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8164a105)
Location: drivers/tty/vt/vt.c:1036
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:con_start
  - drivers/tty/vt/vt.c:con_stop
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:vc_deallocate
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/keyboard.c:fn_inc_console
  - drivers/tty/vt/keyboard.c:fn_dec_console
  - drivers/tty/vt/consolemap.c:console_map_init
  - drivers/tty/vt/consolemap.c:update_user_maps
```
**Symbols:**

```
ffffffff81647080-ffffffff816470a7: vc_cons_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int vc_cons_allocated(unsigned int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8167ebf6)
Location: drivers/tty/vt/vt.c:1036
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:con_start
  - drivers/tty/vt/vt.c:con_stop
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:vc_deallocate
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/keyboard.c:fn_inc_console
  - drivers/tty/vt/keyboard.c:fn_dec_console
  - drivers/tty/vt/consolemap.c:console_map_init
  - drivers/tty/vt/consolemap.c:update_user_maps
```
**Symbols:**

```
ffffffff8167b6c0-ffffffff8167b6e7: vc_cons_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int vc_cons_allocated(unsigned int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff816a1413)
Location: drivers/tty/vt/vt.c:1048
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:con_start
  - drivers/tty/vt/vt.c:con_stop
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:vc_deallocate
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/keyboard.c:fn_inc_console
  - drivers/tty/vt/keyboard.c:fn_dec_console
  - drivers/tty/vt/consolemap.c:console_map_init
  - drivers/tty/vt/consolemap.c:update_user_maps
```
**Symbols:**

```
ffffffff8169deb0-ffffffff8169ded7: vc_cons_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int vc_cons_allocated(unsigned int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81753b25)
Location: drivers/tty/vt/vt.c:1054
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:do_unblank_screen
  - drivers/tty/vt/vt.c:con_start
  - drivers/tty/vt/vt.c:con_stop
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:set_console
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:setterm_command
  - drivers/tty/vt/vt.c:vc_deallocate
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/keyboard.c:fn_inc_console
  - drivers/tty/vt/keyboard.c:fn_dec_console
  - drivers/tty/vt/consolemap.c:console_map_init
  - drivers/tty/vt/consolemap.c:con_unify_unimap
  - drivers/tty/vt/consolemap.c:update_user_maps
```
**Symbols:**

```
ffffffff81750ce0-ffffffff81750d07: vc_cons_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int vc_cons_allocated(unsigned int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8176d564)
Location: drivers/tty/vt/vt.c:1060
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:do_unblank_screen
  - drivers/tty/vt/vt.c:con_start
  - drivers/tty/vt/vt.c:con_stop
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:set_console
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:setterm_command
  - drivers/tty/vt/vt.c:vc_deallocate
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/keyboard.c:fn_inc_console
  - drivers/tty/vt/keyboard.c:fn_dec_console
  - drivers/tty/vt/consolemap.c:console_map_init
  - drivers/tty/vt/consolemap.c:con_unify_unimap
  - drivers/tty/vt/consolemap.c:update_user_maps
```
**Symbols:**

```
ffffffff8176c710-ffffffff8176c737: vc_cons_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int vc_cons_allocated(unsigned int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff817510d4)
Location: drivers/tty/vt/vt.c:1059
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:do_unblank_screen
  - drivers/tty/vt/vt.c:con_start
  - drivers/tty/vt/vt.c:con_stop
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:set_console
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:vc_deallocate
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/keyboard.c:fn_inc_console
  - drivers/tty/vt/keyboard.c:fn_dec_console
  - drivers/tty/vt/consolemap.c:console_map_init
  - drivers/tty/vt/consolemap.c:con_unify_unimap
  - drivers/tty/vt/consolemap.c:update_user_maps
```
**Symbols:**

```
ffffffff817502a0-ffffffff817502c7: vc_cons_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int vc_cons_allocated(unsigned int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff817d3c7d)
Location: drivers/tty/vt/vt.c:1048
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:do_unblank_screen
  - drivers/tty/vt/vt.c:con_start
  - drivers/tty/vt/vt.c:con_stop
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:set_console
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:vc_deallocate
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/keyboard.c:fn_inc_console
  - drivers/tty/vt/keyboard.c:fn_dec_console
  - drivers/tty/vt/consolemap.c:console_map_init
  - drivers/tty/vt/consolemap.c:con_unify_unimap
  - drivers/tty/vt/consolemap.c:update_user_maps
```
**Symbols:**

```
ffffffff817d2ce0-ffffffff817d2d20: vc_cons_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int vc_cons_allocated(unsigned int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81911d16)
Location: drivers/tty/vt/vt.c:1048
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:con_start
  - drivers/tty/vt/vt.c:con_stop
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:set_console
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:vc_deallocate
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/keyboard.c:fn_inc_console
  - drivers/tty/vt/keyboard.c:fn_dec_console
  - drivers/tty/vt/consolemap.c:console_map_init
  - drivers/tty/vt/consolemap.c:con_unify_unimap
  - drivers/tty/vt/consolemap.c:update_user_maps
```
**Symbols:**

```
ffffffff819109b0-ffffffff81910a00: vc_cons_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int vc_cons_allocated(unsigned int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81a6cc86)
Location: drivers/tty/vt/vt.c:1048
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:con_start
  - drivers/tty/vt/vt.c:con_stop
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:set_console
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:vc_deallocate
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/keyboard.c:fn_inc_console
  - drivers/tty/vt/keyboard.c:fn_dec_console
  - drivers/tty/vt/consolemap.c:console_map_init
  - drivers/tty/vt/consolemap.c:con_unify_unimap
  - drivers/tty/vt/consolemap.c:update_user_maps
```
**Symbols:**

```
ffffffff81a6b850-ffffffff81a6b8a0: vc_cons_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int vc_cons_allocated(unsigned int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81ab7396)
Location: drivers/tty/vt/vt.c:998
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:con_start
  - drivers/tty/vt/vt.c:con_stop
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:set_console
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:vc_deallocate
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/keyboard.c:fn_inc_console
  - drivers/tty/vt/keyboard.c:fn_dec_console
  - drivers/tty/vt/consolemap.c:console_map_init
  - drivers/tty/vt/consolemap.c:con_unify_unimap
  - drivers/tty/vt/consolemap.c:update_user_maps
```
**Symbols:**

```
ffffffff81ab5f70-ffffffff81ab5fc0: vc_cons_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int vc_cons_allocated(unsigned int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81b0a096)
Location: drivers/tty/vt/vt.c:997
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:con_start
  - drivers/tty/vt/vt.c:con_stop
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:set_console
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:vc_deallocate
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/keyboard.c:fn_inc_console
  - drivers/tty/vt/keyboard.c:fn_dec_console
  - drivers/tty/vt/consolemap.c:console_map_init
  - drivers/tty/vt/consolemap.c:con_unify_unimap
  - drivers/tty/vt/consolemap.c:update_user_maps
```
**Symbols:**

```
ffffffff81b08c30-ffffffff81b08c80: vc_cons_allocated (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int vc_cons_allocated(unsigned int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffff800010879038)
Location: drivers/tty/vt/vt.c:1048
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:con_start
  - drivers/tty/vt/vt.c:con_stop
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:vc_deallocate
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/keyboard.c:fn_inc_console
  - drivers/tty/vt/keyboard.c:fn_dec_console
  - drivers/tty/vt/consolemap.c:console_map_init
  - drivers/tty/vt/consolemap.c:update_user_maps
```
**Symbols:**

```
ffff8000108755f0-ffff800010875640: vc_cons_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int vc_cons_allocated(unsigned int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (c097b6e8)
Location: drivers/tty/vt/vt.c:1048
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:con_start
  - drivers/tty/vt/vt.c:con_stop
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:vc_deallocate
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/keyboard.c:fn_inc_console
  - drivers/tty/vt/keyboard.c:fn_dec_console
  - drivers/tty/vt/consolemap.c:console_map_init
  - drivers/tty/vt/consolemap.c:con_unify_unimap
  - drivers/tty/vt/consolemap.c:update_user_maps
```
**Symbols:**

```
c097843c-c0978480: vc_cons_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int vc_cons_allocated(unsigned int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (c00000000091b98c)
Location: drivers/tty/vt/vt.c:1048
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:do_unblank_screen
  - drivers/tty/vt/vt.c:con_start
  - drivers/tty/vt/vt.c:con_stop
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:vc_deallocate
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/keyboard.c:fn_inc_console
  - drivers/tty/vt/keyboard.c:fn_dec_console
  - drivers/tty/vt/consolemap.c:console_map_init
  - drivers/tty/vt/consolemap.c:con_unify_unimap
  - drivers/tty/vt/consolemap.c:update_user_maps
```
**Symbols:**

```
c000000000916f40-c000000000916f88: vc_cons_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int vc_cons_allocated(unsigned int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffe00054995a)
Location: drivers/tty/vt/vt.c:1048
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:con_start
  - drivers/tty/vt/vt.c:con_stop
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:vc_deallocate
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/keyboard.c:fn_inc_console
  - drivers/tty/vt/keyboard.c:fn_dec_console
  - drivers/tty/vt/consolemap.c:console_map_init
  - drivers/tty/vt/consolemap.c:con_unify_unimap
  - drivers/tty/vt/consolemap.c:update_user_maps
```
**Symbols:**

```
ffffffe000546da8-ffffffe000546dee: vc_cons_allocated (STB_GLOBAL)
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
int vc_cons_allocated(unsigned int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81666e73)
Location: drivers/tty/vt/vt.c:1048
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:con_start
  - drivers/tty/vt/vt.c:con_stop
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:vc_deallocate
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/keyboard.c:fn_inc_console
  - drivers/tty/vt/keyboard.c:fn_dec_console
  - drivers/tty/vt/consolemap.c:console_map_init
  - drivers/tty/vt/consolemap.c:update_user_maps
```
**Symbols:**

```
ffffffff81663910-ffffffff81663937: vc_cons_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int vc_cons_allocated(unsigned int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff816471f3)
Location: drivers/tty/vt/vt.c:1048
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:con_start
  - drivers/tty/vt/vt.c:con_stop
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:vc_deallocate
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/keyboard.c:fn_inc_console
  - drivers/tty/vt/keyboard.c:fn_dec_console
  - drivers/tty/vt/consolemap.c:console_map_init
  - drivers/tty/vt/consolemap.c:update_user_maps
```
**Symbols:**

```
ffffffff81643c90-ffffffff81643cb7: vc_cons_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int vc_cons_allocated(unsigned int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81695253)
Location: drivers/tty/vt/vt.c:1048
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:con_start
  - drivers/tty/vt/vt.c:con_stop
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:vc_deallocate
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/keyboard.c:fn_inc_console
  - drivers/tty/vt/keyboard.c:fn_dec_console
  - drivers/tty/vt/consolemap.c:console_map_init
  - drivers/tty/vt/consolemap.c:update_user_maps
```
**Symbols:**

```
ffffffff81691cf0-ffffffff81691d17: vc_cons_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int vc_cons_allocated(unsigned int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff816af823)
Location: drivers/tty/vt/vt.c:1048
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:con_start
  - drivers/tty/vt/vt.c:con_stop
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:vc_deallocate
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/keyboard.c:fn_inc_console
  - drivers/tty/vt/keyboard.c:fn_dec_console
  - drivers/tty/vt/consolemap.c:console_map_init
  - drivers/tty/vt/consolemap.c:update_user_maps
```
**Symbols:**

```
ffffffff816ac2e0-ffffffff816ac307: vc_cons_allocated (STB_GLOBAL)
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
