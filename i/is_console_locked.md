# Function: <code>is_console_locked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int is_console_locked();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810d9b30)
Location: kernel/printk/printk.c:2186
Inline: False
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_vc
  - drivers/tty/vt/vc_screen.c:vcs_size
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:vc_deallocate
```
**Symbols:**

```
ffffffff810d9b30-ffffffff810d9b41: is_console_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int is_console_locked();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810decf0)
Location: kernel/printk/printk.c:2256
Inline: False
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_size
  - drivers/tty/vt/vc_screen.c:vcs_vc
  - drivers/tty/vt/vt.c:set_palette
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:save_screen
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
```
**Symbols:**

```
ffffffff810decf0-ffffffff810ded01: is_console_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int is_console_locked();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e5250)
Location: kernel/printk/printk.c:2133
Inline: False
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_size
  - drivers/tty/vt/vc_screen.c:vcs_vc
  - drivers/tty/vt/vt.c:set_palette
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:save_screen
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
```
**Symbols:**

```
ffffffff810e5250-ffffffff810e5261: is_console_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int is_console_locked();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e4540)
Location: kernel/printk/printk.c:2102
Inline: False
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_size
  - drivers/tty/vt/vc_screen.c:vcs_vc
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:save_screen
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
```
**Symbols:**

```
ffffffff810e4540-ffffffff810e4551: is_console_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int is_console_locked();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810ec7f0)
Location: kernel/printk/printk.c:2090
Inline: False
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_size
  - drivers/tty/vt/vc_screen.c:vcs_vc
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:save_screen
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
```
**Symbols:**

```
ffffffff810ec7f0-ffffffff810ec801: is_console_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int is_console_locked();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810f45c0)
Location: kernel/printk/printk.c:2251
Inline: False
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_size
  - drivers/tty/vt/vc_screen.c:vcs_vc
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:save_screen
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
```
**Symbols:**

```
ffffffff810f45c0-ffffffff810f45d1: is_console_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int is_console_locked();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810fcdd0)
Location: kernel/printk/printk.c:2254
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_event_notify
  - drivers/video/fbdev/core/fbcon.c:fbcon_event_notify
  - drivers/video/fbdev/core/fbcon.c:fbcon_event_notify
  - drivers/video/fbdev/core/fbcon.c:fbcon_event_notify
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/vt/vc_screen.c:vcs_size
  - drivers/tty/vt/vc_screen.c:vcs_vc
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:save_screen
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:update_region
  - drivers/tty/vt/vt.c:vc_uniscr_check
```
**Symbols:**

```
ffffffff810fcdd0-ffffffff810fcde1: is_console_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int is_console_locked();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811054c0)
Location: kernel/printk/printk.c:2309
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/vt/vc_screen.c:vcs_size
  - drivers/tty/vt/vc_screen.c:vcs_vc
  - drivers/tty/vt/vt.c:set_palette
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/vt/vt.c:do_unblank_screen
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:con_is_visible
  - drivers/tty/vt/vt.c:con_is_bound
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_allocate
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:save_screen
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:update_region
  - drivers/tty/vt/vt.c:vc_uniscr_check
```
**Symbols:**

```
ffffffff811054c0-ffffffff811054d1: is_console_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int is_console_locked();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81111840)
Location: kernel/printk/printk.c:2319
Inline: False
Direct callers:
  - drivers/video/console/dummycon.c:dummycon_putc
  - drivers/video/console/dummycon.c:dummycon_unregister_output_notifier
  - drivers/video/console/dummycon.c:dummycon_register_output_notifier
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
  - drivers/video/fbdev/core/fbcon.c:fbcon_output_notifier
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vc_screen.c:vcs_size
  - drivers/tty/vt/vc_screen.c:vcs_vc
  - drivers/tty/vt/vt.c:set_palette
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/vt/vt.c:do_unblank_screen
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:con_is_visible
  - drivers/tty/vt/vt.c:con_is_bound
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_allocate
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:save_screen
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:update_region
  - drivers/tty/vt/vt.c:vc_uniscr_check
```
**Symbols:**

```
ffffffff81111840-ffffffff81111851: is_console_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int is_console_locked();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8111cee0)
Location: kernel/printk/printk.c:2339
Inline: False
Direct callers:
  - drivers/video/console/dummycon.c:dummycon_putc
  - drivers/video/console/dummycon.c:dummycon_unregister_output_notifier
  - drivers/video/console/dummycon.c:dummycon_register_output_notifier
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
  - drivers/video/fbdev/core/fbcon.c:fbcon_start
  - drivers/video/fbdev/core/fbcon.c:fbcon_output_notifier
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate
  - drivers/tty/vt/vc_screen.c:vcs_size
  - drivers/tty/vt/vt.c:set_palette
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/vt/vt.c:do_unblank_screen
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_register_con_driver
  - drivers/tty/vt/vt.c:con_is_visible
  - drivers/tty/vt/vt.c:con_is_bound
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_allocate
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:flush_scrollback
  - drivers/tty/vt/vt.c:save_screen
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:update_region
  - drivers/tty/vt/vt.c:vc_uniscr_check
```
**Symbols:**

```
ffffffff8111cee0-ffffffff8111cef1: is_console_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int is_console_locked();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811179b0)
Location: kernel/printk/printk.c:2423
Inline: False
Direct callers:
  - drivers/video/console/dummycon.c:dummycon_putc
  - drivers/video/console/dummycon.c:dummycon_unregister_output_notifier
  - drivers/video/console/dummycon.c:dummycon_register_output_notifier
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
  - drivers/video/fbdev/core/fbcon.c:fbcon_start
  - drivers/video/fbdev/core/fbcon.c:fbcon_output_notifier
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate
  - drivers/tty/vt/vc_screen.c:vcs_size
  - drivers/tty/vt/vt.c:set_palette
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/vt/vt.c:do_unblank_screen
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_register_con_driver
  - drivers/tty/vt/vt.c:con_is_visible
  - drivers/tty/vt/vt.c:con_is_bound
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_allocate
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:flush_scrollback
  - drivers/tty/vt/vt.c:save_screen
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:update_region
  - drivers/tty/vt/vt.c:vc_uniscr_check
```
**Symbols:**

```
ffffffff811179b0-ffffffff811179c1: is_console_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int is_console_locked();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81118090)
Location: kernel/printk/printk.c:2492
Inline: False
Direct callers:
  - drivers/video/console/dummycon.c:dummycon_putc
  - drivers/video/console/dummycon.c:dummycon_unregister_output_notifier
  - drivers/video/console/dummycon.c:dummycon_register_output_notifier
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
  - drivers/video/fbdev/core/fbcon.c:fbcon_output_notifier
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vc_screen.c:vcs_size
  - drivers/tty/vt/vt.c:set_palette
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/vt/vt.c:do_unblank_screen
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_register_con_driver
  - drivers/tty/vt/vt.c:con_is_visible
  - drivers/tty/vt/vt.c:con_is_bound
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_allocate
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:save_screen
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:update_region
  - drivers/tty/vt/vt.c:vc_uniscr_check
```
**Symbols:**

```
ffffffff81118090-ffffffff811180a1: is_console_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int is_console_locked();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811383a0)
Location: kernel/printk/printk.c:2553
Inline: False
Direct callers:
  - drivers/video/console/dummycon.c:dummycon_putc
  - drivers/video/console/dummycon.c:dummycon_unregister_output_notifier
  - drivers/video/console/dummycon.c:dummycon_register_output_notifier
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
  - drivers/video/fbdev/core/fbcon.c:fbcon_output_notifier
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vc_screen.c:vcs_size
  - drivers/tty/vt/vt.c:set_palette
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/vt/vt.c:do_unblank_screen
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_register_con_driver
  - drivers/tty/vt/vt.c:con_is_visible
  - drivers/tty/vt/vt.c:con_is_bound
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vc_con_write_normal
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_allocate
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:save_screen
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:hide_cursor
  - drivers/tty/vt/vt.c:add_softcursor
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:update_region
  - drivers/tty/vt/vt.c:con_scroll
  - drivers/tty/vt/vt.c:vc_uniscr_check
```
**Symbols:**

```
ffffffff811383a0-ffffffff811383b1: is_console_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int is_console_locked();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8115abe0)
Location: kernel/printk/printk.c:2598
Inline: False
Direct callers:
  - drivers/video/console/dummycon.c:dummycon_putc
  - drivers/video/console/dummycon.c:dummycon_unregister_output_notifier
  - drivers/video/console/dummycon.c:dummycon_register_output_notifier
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
  - drivers/video/fbdev/core/fbcon.c:fbcon_output_notifier
  - drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs
  - drivers/video/fbdev/core/fbcon.c:store_rotate_all
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:fbcon_new_modelist
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_blanked
  - drivers/video/fbdev/core/fbcon.c:do_fb_registered
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechange_possible
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechange_possible
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_palette
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_def_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_debug_leave
  - drivers/video/fbdev/core/fbcon.c:fbcon_debug_enter
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_putcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_clear
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vc_screen.c:vcs_size
  - drivers/tty/vt/vt.c:set_palette
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/vt/vt.c:do_unblank_screen
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_register_con_driver
  - drivers/tty/vt/vt.c:con_is_visible
  - drivers/tty/vt/vt.c:con_is_bound
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vc_con_write_normal
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_allocate
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:save_screen
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:hide_cursor
  - drivers/tty/vt/vt.c:add_softcursor
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:update_region
  - drivers/tty/vt/vt.c:con_scroll
  - drivers/tty/vt/vt.c:vc_uniscr_check
```
**Symbols:**

```
ffffffff8115abe0-ffffffff8115abf5: is_console_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int is_console_locked();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8118d0e0)
Location: kernel/printk/printk.c:2688
Inline: False
Direct callers:
  - drivers/video/console/dummycon.c:dummycon_putc
  - drivers/video/console/dummycon.c:dummycon_unregister_output_notifier
  - drivers/video/console/dummycon.c:dummycon_register_output_notifier
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
  - drivers/video/fbdev/core/fbcon.c:fbcon_output_notifier
  - drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs
  - drivers/video/fbdev/core/fbcon.c:store_rotate_all
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:fbcon_new_modelist
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_blanked
  - drivers/video/fbdev/core/fbcon.c:do_fb_registered
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechange_possible
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechange_possible
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_palette
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_def_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_debug_leave
  - drivers/video/fbdev/core/fbcon.c:fbcon_debug_enter
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_putcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_clear
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vc_screen.c:vcs_size
  - drivers/tty/vt/vt.c:set_palette
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/vt/vt.c:do_unblank_screen
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_register_con_driver
  - drivers/tty/vt/vt.c:con_is_visible
  - drivers/tty/vt/vt.c:con_is_bound
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vc_con_write_normal
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_allocate
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:save_screen
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:hide_cursor
  - drivers/tty/vt/vt.c:add_softcursor
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:update_region
  - drivers/tty/vt/vt.c:con_scroll
  - drivers/tty/vt/vt.c:vc_uniscr_check
```
**Symbols:**

```
ffffffff8118d0e0-ffffffff8118d0f5: is_console_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int is_console_locked();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8119e8a0)
Location: kernel/printk/printk.c:2630
Inline: False
Direct callers:
  - drivers/video/console/dummycon.c:dummycon_putc
  - drivers/video/console/dummycon.c:dummycon_unregister_output_notifier
  - drivers/video/console/dummycon.c:dummycon_register_output_notifier
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
  - drivers/video/fbdev/core/fbcon.c:fbcon_output_notifier
  - drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs
  - drivers/video/fbdev/core/fbcon.c:store_rotate_all
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:fbcon_new_modelist
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_blanked
  - drivers/video/fbdev/core/fbcon.c:do_fb_registered
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechange_possible
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechange_possible
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_palette
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_def_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_debug_leave
  - drivers/video/fbdev/core/fbcon.c:fbcon_debug_enter
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_putcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_clear
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vc_screen.c:vcs_size
  - drivers/tty/vt/vt.c:set_palette
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/vt/vt.c:do_unblank_screen
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_register_con_driver
  - drivers/tty/vt/vt.c:con_is_visible
  - drivers/tty/vt/vt.c:con_is_bound
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vc_con_write_normal
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_allocate
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:save_screen
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:hide_cursor
  - drivers/tty/vt/vt.c:add_softcursor
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:update_region
  - drivers/tty/vt/vt.c:con_scroll
  - drivers/tty/vt/vt.c:vc_uniscr_check
```
**Symbols:**

```
ffffffff8119e8a0-ffffffff8119e8b5: is_console_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int is_console_locked();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811ada60)
Location: kernel/printk/printk.c:2667
Inline: False
Direct callers:
  - drivers/video/console/dummycon.c:dummycon_putc
  - drivers/video/console/dummycon.c:dummycon_unregister_output_notifier
  - drivers/video/console/dummycon.c:dummycon_register_output_notifier
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
  - drivers/video/fbdev/core/fbcon.c:fbcon_output_notifier
  - drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs
  - drivers/video/fbdev/core/fbcon.c:store_rotate_all
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:fbcon_new_modelist
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_blanked
  - drivers/video/fbdev/core/fbcon.c:do_fb_registered
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechange_possible
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechange_possible
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_palette
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_def_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_debug_leave
  - drivers/video/fbdev/core/fbcon.c:fbcon_debug_enter
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_putcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_clear
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vc_screen.c:vcs_size
  - drivers/tty/vt/vt.c:set_palette
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/vt/vt.c:do_unblank_screen
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_register_con_driver
  - drivers/tty/vt/vt.c:con_is_visible
  - drivers/tty/vt/vt.c:con_is_bound
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vc_con_write_normal
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_allocate
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:save_screen
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:hide_cursor
  - drivers/tty/vt/vt.c:add_softcursor
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:update_region
  - drivers/tty/vt/vt.c:con_scroll
  - drivers/tty/vt/vt.c:vc_uniscr_check
```
**Symbols:**

```
ffffffff811ada60-ffffffff811ada75: is_console_locked (STB_GLOBAL)
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
int is_console_locked();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffff800010171d28)
Location: kernel/printk/printk.c:2319
Inline: False
Direct callers:
  - drivers/video/console/dummycon.c:dummycon_putc
  - drivers/video/console/dummycon.c:dummycon_unregister_output_notifier
  - drivers/video/console/dummycon.c:dummycon_register_output_notifier
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
  - drivers/video/fbdev/core/fbcon.c:fbcon_output_notifier
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vc_screen.c:vcs_size
  - drivers/tty/vt/vc_screen.c:vcs_vc
  - drivers/tty/vt/vt.c:set_palette
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/vt/vt.c:do_unblank_screen
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:con_is_visible
  - drivers/tty/vt/vt.c:con_is_bound
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_allocate
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:save_screen
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:update_region
  - drivers/tty/vt/vt.c:vc_uniscr_check
```
**Symbols:**

```
ffff800010171d28-ffff800010171d48: is_console_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int is_console_locked();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (c03c46d4)
Location: kernel/printk/printk.c:2319
Inline: False
Direct callers:
  - drivers/video/console/dummycon.c:dummycon_putc
  - drivers/video/console/dummycon.c:dummycon_unregister_output_notifier
  - drivers/video/console/dummycon.c:dummycon_register_output_notifier
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
  - drivers/video/fbdev/core/fbcon.c:fbcon_output_notifier
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vc_screen.c:vcs_size
  - drivers/tty/vt/vc_screen.c:vcs_vc
  - drivers/tty/vt/vt.c:set_palette
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/vt/vt.c:do_unblank_screen
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:con_is_visible
  - drivers/tty/vt/vt.c:con_is_bound
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_allocate
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:save_screen
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:update_region
  - drivers/tty/vt/vt.c:vc_uniscr_check
```
**Symbols:**

```
c03c46d4-c03c46f8: is_console_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int is_console_locked();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (c0000000001ca5d0)
Location: kernel/printk/printk.c:2319
Inline: False
Direct callers:
  - drivers/video/console/dummycon.c:dummycon_putc
  - drivers/video/console/dummycon.c:dummycon_unregister_output_notifier
  - drivers/video/console/dummycon.c:dummycon_register_output_notifier
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
  - drivers/video/fbdev/core/fbcon.c:fbcon_output_notifier
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vc_screen.c:vcs_size
  - drivers/tty/vt/vc_screen.c:vcs_vc
  - drivers/tty/vt/vt.c:set_palette
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/vt/vt.c:do_unblank_screen
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:con_is_visible
  - drivers/tty/vt/vt.c:con_is_bound
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_allocate
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:save_screen
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:update_region
  - drivers/tty/vt/vt.c:vc_uniscr_check
```
**Symbols:**

```
c0000000001ca5d0-c0000000001ca5ec: is_console_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int is_console_locked();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffe00010dfdc)
Location: kernel/printk/printk.c:2319
Inline: False
Direct callers:
  - drivers/video/console/dummycon.c:dummycon_putc
  - drivers/video/console/dummycon.c:dummycon_unregister_output_notifier
  - drivers/video/console/dummycon.c:dummycon_register_output_notifier
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
  - drivers/video/fbdev/core/fbcon.c:fbcon_output_notifier
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vc_screen.c:vcs_size
  - drivers/tty/vt/vc_screen.c:vcs_vc
  - drivers/tty/vt/vt.c:set_palette
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/vt/vt.c:do_unblank_screen
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:con_is_visible
  - drivers/tty/vt/vt.c:con_is_bound
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_allocate
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:save_screen
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:update_region
  - drivers/tty/vt/vt.c:vc_uniscr_check
```
**Symbols:**

```
ffffffe00010dfdc-ffffffe00010dffe: is_console_locked (STB_GLOBAL)
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
int is_console_locked();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81109e20)
Location: kernel/printk/printk.c:2319
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vc_screen.c:vcs_size
  - drivers/tty/vt/vc_screen.c:vcs_vc
  - drivers/tty/vt/vt.c:set_palette
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/vt/vt.c:do_unblank_screen
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:con_is_visible
  - drivers/tty/vt/vt.c:con_is_bound
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_allocate
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:save_screen
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:update_region
  - drivers/tty/vt/vt.c:vc_uniscr_check
```
**Symbols:**

```
ffffffff81109e20-ffffffff81109e31: is_console_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int is_console_locked();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810fad00)
Location: kernel/printk/printk.c:2319
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vc_screen.c:vcs_size
  - drivers/tty/vt/vc_screen.c:vcs_vc
  - drivers/tty/vt/vt.c:set_palette
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/vt/vt.c:do_unblank_screen
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:con_is_visible
  - drivers/tty/vt/vt.c:con_is_bound
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_allocate
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:save_screen
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:update_region
  - drivers/tty/vt/vt.c:vc_uniscr_check
```
**Symbols:**

```
ffffffff810fad00-ffffffff810fad11: is_console_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int is_console_locked();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81107d10)
Location: kernel/printk/printk.c:2319
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vc_screen.c:vcs_size
  - drivers/tty/vt/vc_screen.c:vcs_vc
  - drivers/tty/vt/vt.c:set_palette
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/vt/vt.c:do_unblank_screen
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:con_is_visible
  - drivers/tty/vt/vt.c:con_is_bound
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_allocate
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:save_screen
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:update_region
  - drivers/tty/vt/vt.c:vc_uniscr_check
```
**Symbols:**

```
ffffffff81107d10-ffffffff81107d21: is_console_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int is_console_locked();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811130b0)
Location: kernel/printk/printk.c:2319
Inline: False
Direct callers:
  - drivers/video/console/dummycon.c:dummycon_putc
  - drivers/video/console/dummycon.c:dummycon_unregister_output_notifier
  - drivers/video/console/dummycon.c:dummycon_register_output_notifier
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
  - drivers/video/fbdev/core/fbcon.c:fbcon_output_notifier
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vc_screen.c:vcs_size
  - drivers/tty/vt/vc_screen.c:vcs_vc
  - drivers/tty/vt/vt.c:set_palette
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/vt/vt.c:do_unblank_screen
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:con_is_visible
  - drivers/tty/vt/vt.c:con_is_bound
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_allocate
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:save_screen
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:update_region
  - drivers/tty/vt/vt.c:vc_uniscr_check
```
**Symbols:**

```
ffffffff811130b0-ffffffff811130c1: is_console_locked (STB_GLOBAL)
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
