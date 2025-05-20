# Function: <code>console_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void console_lock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810d6b60)
Location: kernel/printk/printk.c:2139
Inline: False
Direct callers:
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:unregister_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_cpu_notify
  - kernel/printk/printk.c:suspend_console
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:console_device
  - fs/proc/consoles.c:c_start
  - drivers/video/console/fbcon.c:fb_console_init
  - drivers/video/console/fbcon.c:fb_console_init
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:activate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_lseek
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_clear_unimap
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_set_trans_old
  - drivers/tty/vt/consolemap.c:con_set_trans_new
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/tty/vt/consolemap.c:con_get_trans_old
  - drivers/tty/vt/vt.c:give_up_console
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/vt/vt.c:con_install
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:con_get_cmap
  - drivers/tty/vt/vt.c:con_write
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
```
**Symbols:**

```
ffffffff810d6b60-ffffffff810d6b9a: console_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void console_lock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810dbda0)
Location: kernel/printk/printk.c:2209
Inline: False
Direct callers:
  - kernel/printk/printk.c:unregister_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:console_cpu_notify
  - kernel/printk/printk.c:suspend_console
  - fs/proc/consoles.c:c_start
  - drivers/video/console/fbcon.c:fb_console_init
  - drivers/video/console/fbcon.c:fb_console_init
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:activate
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_lseek
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/tty/vt/consolemap.c:con_clear_unimap
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_set_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_old
  - drivers/tty/vt/consolemap.c:con_set_trans_old
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_get_cmap
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:give_up_console
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:con_install
  - drivers/tty/vt/vt.c:con_write
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
```
**Symbols:**

```
ffffffff810dbda0-ffffffff810dbdda: console_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void console_lock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e2dc0)
Location: kernel/printk/printk.c:2086
Inline: False
Direct callers:
  - kernel/printk/printk.c:unregister_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:console_cpu_notify
  - kernel/printk/printk.c:suspend_console
  - fs/proc/consoles.c:c_start
  - drivers/video/console/fbcon.c:fb_console_init
  - drivers/video/console/fbcon.c:fb_console_init
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:activate
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_lseek
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/tty/vt/consolemap.c:con_clear_unimap
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_set_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_old
  - drivers/tty/vt/consolemap.c:con_set_trans_old
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_get_cmap
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:give_up_console
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:con_install
  - drivers/tty/vt/vt.c:con_write
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
```
**Symbols:**

```
ffffffff810e2dc0-ffffffff810e2dfa: console_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void console_lock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e1eb0)
Location: kernel/printk/printk.c:2055
Inline: False
Direct callers:
  - kernel/printk/printk.c:unregister_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:suspend_console
  - fs/proc/consoles.c:c_start
  - drivers/video/console/fbcon.c:fb_console_init
  - drivers/video/console/fbcon.c:fb_console_init
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:activate
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_lseek
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/tty/vt/consolemap.c:con_clear_unimap
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_set_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_old
  - drivers/tty/vt/consolemap.c:con_set_trans_old
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_get_cmap
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:give_up_console
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:con_install
  - drivers/tty/vt/vt.c:con_write
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
```
**Symbols:**

```
ffffffff810e1eb0-ffffffff810e1eea: console_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void console_lock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e9f90)
Location: kernel/printk/printk.c:2043
Inline: False
Direct callers:
  - kernel/printk/printk.c:unregister_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:suspend_console
  - fs/proc/consoles.c:c_start
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:activate
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_lseek
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/tty/vt/consolemap.c:con_clear_unimap
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_set_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_old
  - drivers/tty/vt/consolemap.c:con_set_trans_old
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_get_cmap
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:give_up_console
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:con_install
  - drivers/tty/vt/vt.c:con_write
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
```
**Symbols:**

```
ffffffff810e9f90-ffffffff810e9fca: console_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void console_lock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810f2250)
Location: kernel/printk/printk.c:2217
Inline: False
Direct callers:
  - kernel/printk/printk.c:unregister_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:suspend_console
  - fs/proc/consoles.c:c_start
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:unbind_console
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:activate
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_lseek
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/tty/vt/consolemap.c:con_clear_unimap
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_set_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_old
  - drivers/tty/vt/consolemap.c:con_set_trans_old
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_get_cmap
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:give_up_console
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:con_install
  - drivers/tty/vt/vt.c:con_write
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
```
**Symbols:**

```
ffffffff810f2250-ffffffff810f228a: console_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void console_lock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810fd9a0)
Location: kernel/printk/printk.c:2220
Inline: False
Direct callers:
  - kernel/printk/printk.c:unregister_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:suspend_console
  - fs/proc/consoles.c:c_start
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:unbind_console
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:activate
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_lseek
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/tty/vt/consolemap.c:con_clear_unimap
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_set_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_old
  - drivers/tty/vt/consolemap.c:con_set_trans_old
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_get_cmap
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:give_up_console
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:con_install
  - drivers/tty/vt/vt.c:con_write
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
```
**Symbols:**

```
ffffffff810fd9a0-ffffffff810fd9da: console_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void console_lock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81105ce0)
Location: kernel/printk/printk.c:2275
Inline: False
Direct callers:
  - kernel/printk/printk.c:unregister_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:suspend_console
  - fs/proc/consoles.c:c_start
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:activate
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_rotate
  - drivers/video/fbdev/core/fbcon.c:store_rotate_all
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_lseek
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/tty/vt/consolemap.c:con_clear_unimap
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_set_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_old
  - drivers/tty/vt/consolemap.c:con_set_trans_old
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_get_cmap
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:give_up_console
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/tty/vt/vt.c:show_bind
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:con_install
  - drivers/tty/vt/vt.c:con_write
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
```
**Symbols:**

```
ffffffff81105ce0-ffffffff81105d1a: console_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void console_lock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81112060)
Location: kernel/printk/printk.c:2285
Inline: False
Direct callers:
  - kernel/printk/printk.c:unregister_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:suspend_console
  - fs/proc/consoles.c:c_start
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:activate
  - drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_rotate
  - drivers/video/fbdev/core/fbcon.c:store_rotate_all
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_lseek
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:set_selection_kernel
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/tty/vt/consolemap.c:con_clear_unimap
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_set_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_old
  - drivers/tty/vt/consolemap.c:con_set_trans_old
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_get_cmap
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:give_up_console
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/tty/vt/vt.c:show_bind
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:con_install
  - drivers/tty/vt/vt.c:con_write
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
```
**Symbols:**

```
ffffffff81112060-ffffffff8111209a: console_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void console_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8111ef25)
Location: kernel/printk/printk.c:2305
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_unblank
Direct callers:
  - kernel/printk/printk.c:unregister_console
  - kernel/printk/printk.c:suspend_console
  - fs/proc/consoles.c:c_start
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_rotate
  - drivers/video/fbdev/core/fbsysfs.c:store_bpp
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_mode
  - drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_rotate
  - drivers/video/fbdev/core/fbcon.c:store_rotate_all
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_lseek
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:set_selection_user
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/tty/vt/consolemap.c:con_clear_unimap
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_set_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_old
  - drivers/tty/vt/consolemap.c:con_set_trans_old
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_get
  - drivers/tty/vt/vt.c:con_font_get
  - drivers/tty/vt/vt.c:con_get_cmap
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:give_up_console
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/tty/vt/vt.c:show_bind
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:con_install
  - drivers/tty/vt/vt.c:con_write
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/kgdboc.c:kgdboc_earlycon_init
```
**Symbols:**

```
ffffffff8111d920-ffffffff8111d95a: console_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void console_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811198c5)
Location: kernel/printk/printk.c:2389
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_unblank
Direct callers:
  - kernel/printk/printk.c:unregister_console
  - kernel/printk/printk.c:suspend_console
  - fs/proc/consoles.c:c_start
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_rotate
  - drivers/video/fbdev/core/fbsysfs.c:store_bpp
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_mode
  - drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_rotate
  - drivers/video/fbdev/core/fbcon.c:store_rotate_all
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate
  - drivers/tty/vt/vt_ioctl.c:vt_setactivate
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_lseek
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:set_selection_user
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/tty/vt/consolemap.c:con_clear_unimap
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_set_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_old
  - drivers/tty/vt/consolemap.c:con_set_trans_old
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_get
  - drivers/tty/vt/vt.c:con_font_get
  - drivers/tty/vt/vt.c:con_get_cmap
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:give_up_console
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/tty/vt/vt.c:show_bind
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:con_install
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/kgdboc.c:kgdboc_earlycon_init
```
**Symbols:**

```
ffffffff81118380-ffffffff811183ba: console_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void console_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8111a445)
Location: kernel/printk/printk.c:2458
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_unblank
Direct callers:
  - kernel/printk/printk.c:unregister_console
  - kernel/printk/printk.c:suspend_console
  - fs/proc/consoles.c:c_start
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_rotate
  - drivers/video/fbdev/core/fbsysfs.c:store_bpp
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_mode
  - drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_rotate
  - drivers/video/fbdev/core/fbcon.c:store_rotate_all
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_resizex
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_lseek
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:set_selection_kernel
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/tty/vt/consolemap.c:con_clear_unimap
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_set_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_old
  - drivers/tty/vt/consolemap.c:con_set_trans_old
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_get
  - drivers/tty/vt/vt.c:con_font_get
  - drivers/tty/vt/vt.c:con_get_cmap
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:give_up_console
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/tty/vt/vt.c:show_bind
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:con_install
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/kgdboc.c:kgdboc_earlycon_init
```
**Symbols:**

```
ffffffff811189c0-ffffffff811189fa: console_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void console_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8113ab05)
Location: kernel/printk/printk.c:2519
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_unblank
Direct callers:
  - kernel/printk/printk.c:unregister_console
  - kernel/printk/printk.c:suspend_console
  - fs/proc/consoles.c:c_start
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_rotate
  - drivers/video/fbdev/core/fbsysfs.c:store_bpp
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_mode
  - drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_rotate
  - drivers/video/fbdev/core/fbcon.c:store_rotate_all
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_resizex
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_lseek
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:set_selection_kernel
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/tty/vt/consolemap.c:con_clear_unimap
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_set_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_old
  - drivers/tty/vt/consolemap.c:con_set_trans_old
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_get
  - drivers/tty/vt/vt.c:con_font_get
  - drivers/tty/vt/vt.c:con_get_cmap
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:give_up_console
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/tty/vt/vt.c:show_bind
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:con_shutdown
  - drivers/tty/vt/vt.c:con_install
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/kgdboc.c:kgdboc_earlycon_init
```
**Symbols:**

```
ffffffff81138b40-ffffffff81138b7a: console_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void console_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8115d3a8)
Location: kernel/printk/printk.c:2564
Inline: True
Inline callers:
  - kernel/printk/printk.c:__pr_flush
  - kernel/printk/printk.c:__pr_flush
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_unblank
Direct callers:
  - kernel/printk/printk.c:unregister_console
  - kernel/printk/printk.c:suspend_console
  - fs/proc/consoles.c:c_start
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:activate
  - drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_rotate
  - drivers/video/fbdev/core/fbcon.c:store_rotate_all
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_resizex
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_lseek
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:set_selection_kernel
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/tty/vt/consolemap.c:con_clear_unimap
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_set_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_old
  - drivers/tty/vt/consolemap.c:con_set_trans_old
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_get
  - drivers/tty/vt/vt.c:con_get_cmap
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:give_up_console
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/tty/vt/vt.c:show_bind
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:con_shutdown
  - drivers/tty/vt/vt.c:con_install
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/kgdboc.c:kgdboc_earlycon_init
```
**Symbols:**

```
ffffffff8115bc40-ffffffff8115bc82: console_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void console_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811907c7)
Location: kernel/printk/printk.c:2654
Inline: True
Inline callers:
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:suspend_console
  - kernel/printk/printk.c:suspend_console
Direct callers:
  - fs/proc/consoles.c:show_console_dev
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:activate
  - drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_rotate
  - drivers/video/fbdev/core/fbcon.c:store_rotate_all
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_resizex
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_lseek
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:set_selection_kernel
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/tty/vt/consolemap.c:con_clear_unimap
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_set_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_old
  - drivers/tty/vt/consolemap.c:con_set_trans_old
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_get
  - drivers/tty/vt/vt.c:con_get_cmap
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:give_up_console
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/tty/vt/vt.c:show_bind
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:con_shutdown
  - drivers/tty/vt/vt.c:con_install
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffffffff8118e670-ffffffff8118e6b2: console_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void console_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811a20da)
Location: kernel/printk/printk.c:2596
Inline: True
Inline callers:
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:suspend_console
  - kernel/printk/printk.c:suspend_console
Direct callers:
  - fs/proc/consoles.c:show_console_dev
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:activate
  - drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_rotate
  - drivers/video/fbdev/core/fbcon.c:store_rotate_all
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_resizex
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_lseek
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:set_selection_kernel
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/tty/vt/consolemap.c:con_clear_unimap
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_set_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_old
  - drivers/tty/vt/consolemap.c:con_set_trans_old
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_get
  - drivers/tty/vt/vt.c:con_font_get
  - drivers/tty/vt/vt.c:con_get_cmap
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:give_up_console
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/tty/vt/vt.c:show_bind
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:con_shutdown
  - drivers/tty/vt/vt.c:con_install
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffffffff8119ffd0-ffffffff811a0012: console_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void console_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811b2ccf)
Location: kernel/printk/printk.c:2632
Inline: True
Inline callers:
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_unblank
Direct callers:
  - fs/proc/consoles.c:show_console_dev
  - drivers/video/fbdev/core/fb_chrdev.c:do_fb_ioctl
  - drivers/video/fbdev/core/fb_chrdev.c:do_fb_ioctl
  - drivers/video/fbdev/core/fb_chrdev.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:activate
  - drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_rotate
  - drivers/video/fbdev/core/fbcon.c:store_rotate_all
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_resizex
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_lseek
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:set_selection_kernel
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/tty/vt/consolemap.c:con_clear_unimap
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_set_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_old
  - drivers/tty/vt/consolemap.c:con_set_trans_old
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_get
  - drivers/tty/vt/vt.c:con_font_get
  - drivers/tty/vt/vt.c:con_get_cmap
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:give_up_console
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/tty/vt/vt.c:show_bind
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:con_shutdown
  - drivers/tty/vt/vt.c:con_install
  - drivers/tty/vt/vt.c:con_write
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
  - drivers/gpu/drm/drm_fb_helper.c:drm_fb_helper_resume_worker
```
**Symbols:**

```
ffffffff811af600-ffffffff811af66d: console_lock (STB_GLOBAL)
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
void console_lock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffff800010172408)
Location: kernel/printk/printk.c:2285
Inline: False
Direct callers:
  - kernel/printk/printk.c:unregister_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:suspend_console
  - fs/proc/consoles.c:c_start
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:activate
  - drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_rotate
  - drivers/video/fbdev/core/fbcon.c:store_rotate_all
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/video/fbdev/mx3fb.c:mx3fb_resume
  - drivers/video/fbdev/mx3fb.c:mx3fb_suspend
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_lseek
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:set_selection_kernel
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/tty/vt/consolemap.c:con_clear_unimap
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_set_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_old
  - drivers/tty/vt/consolemap.c:con_set_trans_old
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_get_cmap
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:give_up_console
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/tty/vt/vt.c:show_bind
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:con_install
  - drivers/tty/vt/vt.c:con_write
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
```
**Symbols:**

```
ffff800010172408-ffff80001017244c: console_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void console_lock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (c03c502c)
Location: kernel/printk/printk.c:2285
Inline: False
Direct callers:
  - kernel/printk/printk.c:unregister_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:suspend_console
  - fs/proc/consoles.c:c_start
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:activate
  - drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_rotate
  - drivers/video/fbdev/core/fbcon.c:store_rotate_all
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/video/fbdev/mx3fb.c:mx3fb_resume
  - drivers/video/fbdev/mx3fb.c:mx3fb_suspend
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_lseek
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:set_selection_kernel
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/tty/vt/consolemap.c:con_clear_unimap
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_set_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_old
  - drivers/tty/vt/consolemap.c:con_set_trans_old
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_get_cmap
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:give_up_console
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/tty/vt/vt.c:show_bind
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:con_install
  - drivers/tty/vt/vt.c:con_write
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
```
**Symbols:**

```
c03c502c-c03c5070: console_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void console_lock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (c0000000001cb920)
Location: kernel/printk/printk.c:2285
Inline: False
Direct callers:
  - kernel/printk/printk.c:unregister_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:suspend_console
  - fs/proc/consoles.c:c_start
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:activate
  - drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_rotate
  - drivers/video/fbdev/core/fbcon.c:store_rotate_all
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_lseek
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:set_selection_kernel
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/tty/vt/consolemap.c:con_clear_unimap
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_set_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_old
  - drivers/tty/vt/consolemap.c:con_set_trans_old
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_get_cmap
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:give_up_console
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/tty/vt/vt.c:show_bind
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:con_shutdown
  - drivers/tty/vt/vt.c:con_install
  - drivers/tty/vt/vt.c:con_write
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
```
**Symbols:**

```
c0000000001cb920-c0000000001cb988: console_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void console_lock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffe00010e784)
Location: kernel/printk/printk.c:2285
Inline: False
Direct callers:
  - kernel/printk/printk.c:unregister_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:suspend_console
  - fs/proc/consoles.c:c_start
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:activate
  - drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_rotate
  - drivers/video/fbdev/core/fbcon.c:store_rotate_all
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_lseek
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:set_selection_kernel
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/tty/vt/consolemap.c:con_clear_unimap
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_set_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_old
  - drivers/tty/vt/consolemap.c:con_set_trans_old
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_get_cmap
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:give_up_console
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/tty/vt/vt.c:show_bind
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:con_install
  - drivers/tty/vt/vt.c:con_write
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
```
**Symbols:**

```
ffffffe00010e784-ffffffe00010e7d2: console_lock (STB_GLOBAL)
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
void console_lock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8110a640)
Location: kernel/printk/printk.c:2285
Inline: False
Direct callers:
  - kernel/printk/printk.c:unregister_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:suspend_console
  - fs/proc/consoles.c:c_start
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:activate
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_rotate
  - drivers/video/fbdev/core/fbcon.c:store_rotate_all
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_lseek
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:set_selection_kernel
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/tty/vt/consolemap.c:con_clear_unimap
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_set_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_old
  - drivers/tty/vt/consolemap.c:con_set_trans_old
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_get_cmap
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:give_up_console
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/tty/vt/vt.c:show_bind
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:con_install
  - drivers/tty/vt/vt.c:con_write
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
```
**Symbols:**

```
ffffffff8110a640-ffffffff8110a67a: console_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void console_lock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810fb520)
Location: kernel/printk/printk.c:2285
Inline: False
Direct callers:
  - kernel/printk/printk.c:unregister_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:suspend_console
  - fs/proc/consoles.c:c_start
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:activate
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_rotate
  - drivers/video/fbdev/core/fbcon.c:store_rotate_all
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_lseek
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:set_selection_kernel
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/tty/vt/consolemap.c:con_clear_unimap
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_set_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_old
  - drivers/tty/vt/consolemap.c:con_set_trans_old
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_get_cmap
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:give_up_console
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/tty/vt/vt.c:show_bind
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:con_install
  - drivers/tty/vt/vt.c:con_write
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
```
**Symbols:**

```
ffffffff810fb520-ffffffff810fb55a: console_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void console_lock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81108530)
Location: kernel/printk/printk.c:2285
Inline: False
Direct callers:
  - kernel/printk/printk.c:unregister_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:suspend_console
  - fs/proc/consoles.c:c_start
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:activate
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_rotate
  - drivers/video/fbdev/core/fbcon.c:store_rotate_all
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_lseek
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:set_selection_kernel
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/tty/vt/consolemap.c:con_clear_unimap
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_set_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_old
  - drivers/tty/vt/consolemap.c:con_set_trans_old
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_get_cmap
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:give_up_console
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/tty/vt/vt.c:show_bind
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:con_install
  - drivers/tty/vt/vt.c:con_write
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
```
**Symbols:**

```
ffffffff81108530-ffffffff8110856a: console_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void console_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81116bea)
Location: kernel/printk/printk.c:2285
Inline: True
Inline callers:
  - kernel/printk/printk.c:unregister_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:suspend_console
Direct callers:
  - fs/proc/consoles.c:c_start
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:activate
  - drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_rotate
  - drivers/video/fbdev/core/fbcon.c:store_rotate_all
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_lseek
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:set_selection_kernel
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/tty/vt/consolemap.c:con_clear_unimap
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_set_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_old
  - drivers/tty/vt/consolemap.c:con_set_trans_old
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_get_cmap
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:give_up_console
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/tty/vt/vt.c:show_bind
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:con_install
  - drivers/tty/vt/vt.c:con_write
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
```
**Symbols:**

```
ffffffff811138d0-ffffffff81113905: console_lock (STB_GLOBAL)
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
