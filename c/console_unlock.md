# Function: <code>console_unlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void console_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810d7a00)
Location: kernel/printk/printk.c:2234
Inline: True
Direct callers:
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:unregister_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_cpu_notify
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:resume_console
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_device
  - fs/proc/consoles.c:c_stop
  - drivers/video/console/fbcon.c:fb_flashcursor
  - drivers/video/console/fbcon.c:fb_console_init
  - drivers/video/console/fbcon.c:fb_console_init
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:activate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
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
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
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
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/tty/vt/consolemap.c:con_get_trans_old
  - drivers/tty/vt/vt.c:give_up_console
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/vt/vt.c:con_init
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
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
```
**Symbols:**

```
ffffffff810d7a00-ffffffff810d7f50: console_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void console_unlock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810dc970)
Location: kernel/printk/printk.c:2339
Inline: False
Direct callers:
  - kernel/printk/printk.c:unregister_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:console_cpu_notify
  - kernel/printk/printk.c:resume_console
  - kernel/printk/printk.c:vprintk_emit
  - fs/proc/consoles.c:c_stop
  - drivers/video/console/fbcon.c:fb_console_init
  - drivers/video/console/fbcon.c:fb_console_init
  - drivers/video/console/fbcon.c:fb_flashcursor
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:activate
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
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
ffffffff810dc970-ffffffff810dcf6a: console_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void console_unlock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e3160)
Location: kernel/printk/printk.c:2180
Inline: False
Direct callers:
  - kernel/printk/printk.c:unregister_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:console_cpu_notify
  - kernel/printk/printk.c:resume_console
  - kernel/printk/printk.c:vprintk_emit
  - fs/proc/consoles.c:c_stop
  - drivers/video/console/fbcon.c:fb_console_init
  - drivers/video/console/fbcon.c:fb_console_init
  - drivers/video/console/fbcon.c:fb_flashcursor
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:activate
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
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
ffffffff810e3160-ffffffff810e3607: console_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void console_unlock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e2720)
Location: kernel/printk/printk.c:2149
Inline: False
Direct callers:
  - kernel/printk/printk.c:unregister_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:resume_console
  - kernel/printk/printk.c:vprintk_emit
  - fs/proc/consoles.c:c_stop
  - drivers/video/console/fbcon.c:fb_console_init
  - drivers/video/console/fbcon.c:fb_console_init
  - drivers/video/console/fbcon.c:fb_flashcursor
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:activate
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
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
ffffffff810e2720-ffffffff810e2bed: console_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void console_unlock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810ea5e0)
Location: kernel/printk/printk.c:2137
Inline: False
Direct callers:
  - kernel/printk/printk.c:unregister_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:resume_console
  - kernel/printk/printk.c:vprintk_emit
  - fs/proc/consoles.c:c_stop
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:activate
  - drivers/video/fbdev/core/fbcon.c:fb_flashcursor
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
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
ffffffff810ea5e0-ffffffff810eaab5: console_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void console_unlock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810f29c0)
Location: kernel/printk/printk.c:2298
Inline: False
Direct callers:
  - kernel/printk/printk.c:unregister_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:resume_console
  - kernel/printk/printk.c:vprintk_emit
  - fs/proc/consoles.c:c_stop
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:unbind_console
  - drivers/video/fbdev/core/fbmem.c:unbind_console
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:activate
  - drivers/video/fbdev/core/fbcon.c:fb_flashcursor
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
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
ffffffff810f29c0-ffffffff810f2e83: console_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void console_unlock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810fe000)
Location: kernel/printk/printk.c:2302
Inline: False
Direct callers:
  - kernel/printk/printk.c:unregister_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:resume_console
  - kernel/printk/printk.c:vprintk_emit
  - fs/proc/consoles.c:c_stop
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:unbind_console
  - drivers/video/fbdev/core/fbmem.c:unbind_console
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:activate
  - drivers/video/fbdev/core/fbcon.c:fb_flashcursor
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
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
ffffffff810fe000-ffffffff810fe51e: console_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void console_unlock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81106730)
Location: kernel/printk/printk.c:2357
Inline: False
Direct callers:
  - kernel/printk/printk.c:unregister_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:resume_console
  - kernel/printk/printk.c:vprintk_emit
  - fs/proc/consoles.c:c_stop
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:activate
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_rotate
  - drivers/video/fbdev/core/fbcon.c:store_rotate_all
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fb_flashcursor
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
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
ffffffff81106730-ffffffff81106c03: console_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void console_unlock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81112ac0)
Location: kernel/printk/printk.c:2367
Inline: False
Direct callers:
  - kernel/printk/printk.c:unregister_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:resume_console
  - kernel/printk/printk.c:vprintk_emit
  - fs/proc/consoles.c:c_stop
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:activate
  - drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_rotate
  - drivers/video/fbdev/core/fbcon.c:store_rotate_all
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fb_flashcursor
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
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
ffffffff81112ac0-ffffffff81112f93: console_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void console_unlock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8111ea80)
Location: kernel/printk/printk.c:2387
Inline: False
Direct callers:
  - kernel/printk/printk.c:unregister_console
  - kernel/printk/printk.c:unregister_console
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:resume_console
  - kernel/printk/printk.c:vprintk_emit
  - fs/proc/consoles.c:c_stop
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_rotate
  - drivers/video/fbdev/core/fbsysfs.c:store_rotate
  - drivers/video/fbdev/core/fbsysfs.c:store_bpp
  - drivers/video/fbdev/core/fbsysfs.c:store_bpp
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_mode
  - drivers/video/fbdev/core/fbsysfs.c:store_mode
  - drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_rotate
  - drivers/video/fbdev/core/fbcon.c:store_rotate_all
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fb_flashcursor
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
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
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate
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
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_get
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
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:con_install
  - drivers/tty/vt/vt.c:con_write
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/kgdboc.c:kgdboc_earlycon_init
```
**Symbols:**

```
ffffffff8111ea80-ffffffff8111eecd: console_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void console_unlock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811194d0)
Location: kernel/printk/printk.c:2471
Inline: False
Direct callers:
  - kernel/printk/printk.c:unregister_console
  - kernel/printk/printk.c:unregister_console
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:resume_console
  - kernel/printk/printk.c:vprintk_emit
  - fs/proc/consoles.c:c_stop
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_rotate
  - drivers/video/fbdev/core/fbsysfs.c:store_rotate
  - drivers/video/fbdev/core/fbsysfs.c:store_bpp
  - drivers/video/fbdev/core/fbsysfs.c:store_bpp
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_mode
  - drivers/video/fbdev/core/fbsysfs.c:store_mode
  - drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_rotate
  - drivers/video/fbdev/core/fbcon.c:store_rotate_all
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fb_flashcursor
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
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
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate
  - drivers/tty/vt/vt_ioctl.c:vt_setactivate
  - drivers/tty/vt/vt_ioctl.c:vt_setactivate
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_lseek
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
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_get
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
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:con_install
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/kgdboc.c:kgdboc_earlycon_init
```
**Symbols:**

```
ffffffff811194d0-ffffffff8111986b: console_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void console_unlock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8111a050)
Location: kernel/printk/printk.c:2540
Inline: False
Direct callers:
  - kernel/printk/printk.c:unregister_console
  - kernel/printk/printk.c:unregister_console
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:resume_console
  - kernel/printk/printk.c:vprintk_emit
  - fs/proc/consoles.c:c_stop
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_rotate
  - drivers/video/fbdev/core/fbsysfs.c:store_rotate
  - drivers/video/fbdev/core/fbsysfs.c:store_bpp
  - drivers/video/fbdev/core/fbsysfs.c:store_bpp
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_mode
  - drivers/video/fbdev/core/fbsysfs.c:store_mode
  - drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_rotate
  - drivers/video/fbdev/core/fbcon.c:store_rotate_all
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fb_flashcursor
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
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
  - drivers/tty/vt/vt_ioctl.c:vt_resizex
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_lseek
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
  - drivers/tty/vt/vt.c:con_font_get
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
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:con_install
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/kgdboc.c:kgdboc_earlycon_init
```
**Symbols:**

```
ffffffff8111a050-ffffffff8111a3e1: console_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void console_unlock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:2601
Inline: False
Direct callers:
  - kernel/printk/printk.c:unregister_console
  - kernel/printk/printk.c:unregister_console
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:resume_console
  - kernel/printk/printk.c:vprintk_emit
  - fs/proc/consoles.c:c_stop
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_rotate
  - drivers/video/fbdev/core/fbsysfs.c:store_rotate
  - drivers/video/fbdev/core/fbsysfs.c:store_bpp
  - drivers/video/fbdev/core/fbsysfs.c:store_bpp
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_mode
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
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fb_flashcursor
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
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
  - drivers/tty/vt/vt_ioctl.c:vt_resizex
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_lseek
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
  - drivers/tty/vt/vt.c:con_font_get
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
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:con_shutdown
  - drivers/tty/vt/vt.c:con_install
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/kgdboc.c:kgdboc_earlycon_init
```
**Symbols:**

```
ffffffff81cac216-ffffffff81cac261: console_unlock.cold (STB_LOCAL)
ffffffff8113a720-ffffffff8113aaa5: console_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void console_unlock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:2833
Inline: False
Direct callers:
  - kernel/printk/printk.c:__pr_flush
  - kernel/printk/printk.c:__pr_flush
  - kernel/printk/printk.c:unregister_console
  - kernel/printk/printk.c:unregister_console
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:resume_console
  - kernel/printk/printk.c:vprintk_emit
  - fs/proc/consoles.c:c_stop
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
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
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
  - drivers/tty/vt/vt_ioctl.c:vt_resizex
  - drivers/tty/vt/vt_ioctl.c:vt_resizex
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_lseek
  - drivers/tty/vt/vc_screen.c:vcs_lseek
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:set_selection_kernel
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/tty/vt/consolemap.c:con_set_unimap
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
  - drivers/tty/vt/vt.c:con_font_get
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
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:con_shutdown
  - drivers/tty/vt/vt.c:con_install
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/kgdboc.c:kgdboc_earlycon_init
```
**Symbols:**

```
ffffffff81e5c76e-ffffffff81e5c797: console_unlock.cold (STB_LOCAL)
ffffffff8115d180-ffffffff8115d362: console_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void console_unlock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:2938
Inline: False
Direct callers:
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:resume_console
  - kernel/printk/printk.c:vprintk_emit
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
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
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
  - drivers/tty/vt/vt_ioctl.c:vt_resizex
  - drivers/tty/vt/vt_ioctl.c:vt_resizex
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_lseek
  - drivers/tty/vt/vc_screen.c:vcs_lseek
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:set_selection_kernel
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/tty/vt/consolemap.c:con_clear_unimap
  - drivers/tty/vt/consolemap.c:con_clear_unimap
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_set_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_old
  - drivers/tty/vt/consolemap.c:con_set_trans_old
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_get
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
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:con_shutdown
  - drivers/tty/vt/vt.c:con_install
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffffffff82058a51-ffffffff82058a66: console_unlock.cold (STB_LOCAL)
ffffffff81190040-ffffffff81190137: console_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void console_unlock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:2979
Inline: False
Direct callers:
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:resume_console
  - kernel/printk/printk.c:vprintk_emit
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
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
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
  - drivers/tty/vt/vt_ioctl.c:vt_resizex
  - drivers/tty/vt/vt_ioctl.c:vt_resizex
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_lseek
  - drivers/tty/vt/vc_screen.c:vcs_lseek
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:set_selection_kernel
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/tty/vt/consolemap.c:con_clear_unimap
  - drivers/tty/vt/consolemap.c:con_clear_unimap
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_set_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_old
  - drivers/tty/vt/consolemap.c:con_set_trans_old
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_get
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
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:con_shutdown
  - drivers/tty/vt/vt.c:con_install
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffffffff820d72cf-ffffffff820d72e4: console_unlock.cold (STB_LOCAL)
ffffffff811a1830-ffffffff811a1927: console_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void console_unlock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:3013
Inline: False
Direct callers:
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:vprintk_emit
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
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
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
  - drivers/tty/vt/vt_ioctl.c:vt_resizex
  - drivers/tty/vt/vt_ioctl.c:vt_resizex
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_lseek
  - drivers/tty/vt/vc_screen.c:vcs_lseek
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:set_selection_kernel
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/tty/vt/consolemap.c:con_clear_unimap
  - drivers/tty/vt/consolemap.c:con_clear_unimap
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_set_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_old
  - drivers/tty/vt/consolemap.c:con_set_trans_old
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_get
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
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:con_shutdown
  - drivers/tty/vt/vt.c:con_install
  - drivers/tty/vt/vt.c:con_write
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
  - drivers/gpu/drm/drm_fb_helper.c:drm_fb_helper_resume_worker
```
**Symbols:**

```
ffffffff821b2639-ffffffff821b264e: console_unlock.cold (STB_LOCAL)
ffffffff811b1f50-ffffffff811b2048: console_unlock (STB_GLOBAL)
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
void console_unlock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffff800010173e78)
Location: kernel/printk/printk.c:2367
Inline: False
Direct callers:
  - kernel/printk/printk.c:unregister_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:resume_console
  - kernel/printk/printk.c:vprintk_emit
  - fs/proc/consoles.c:c_stop
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
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_rotate
  - drivers/video/fbdev/core/fbcon.c:store_rotate_all
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fb_flashcursor
  - drivers/video/fbdev/core/fbcon.c:fb_flashcursor
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/video/fbdev/mx3fb.c:mx3fb_resume
  - drivers/video/fbdev/mx3fb.c:mx3fb_suspend
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
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
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
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
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:con_install
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
ffff800010173e78-ffff800010174444: console_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void console_unlock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (c03c60d0)
Location: kernel/printk/printk.c:2367
Inline: False
Direct callers:
  - kernel/printk/printk.c:unregister_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:resume_console
  - kernel/printk/printk.c:vprintk_emit
  - fs/proc/consoles.c:c_stop
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
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fb_flashcursor
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/video/fbdev/mx3fb.c:mx3fb_resume
  - drivers/video/fbdev/mx3fb.c:mx3fb_suspend
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
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
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_lseek
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:set_selection_kernel
  - drivers/tty/vt/consolemap.c:con_get_unimap
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
  - drivers/tty/vt/vt.c:con_font_op
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
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:con_install
  - drivers/tty/vt/vt.c:con_write
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
c03c60d0-c03c6654: console_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void console_unlock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (c0000000001ccb60)
Location: kernel/printk/printk.c:2367
Inline: False
Direct callers:
  - kernel/printk/printk.c:unregister_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:resume_console
  - kernel/printk/printk.c:vprintk_emit
  - fs/proc/consoles.c:c_stop
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
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_rotate
  - drivers/video/fbdev/core/fbcon.c:store_rotate_all
  - drivers/video/fbdev/core/fbcon.c:store_rotate_all
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fb_flashcursor
  - drivers/video/fbdev/core/fbcon.c:fb_flashcursor
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
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
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vc_screen.c:vcs_open
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
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:con_shutdown
  - drivers/tty/vt/vt.c:con_install
  - drivers/tty/vt/vt.c:con_install
  - drivers/tty/vt/vt.c:con_install
  - drivers/tty/vt/vt.c:con_write
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
c0000000001ccb60-c0000000001cd2a4: console_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void console_unlock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffe00010f20a)
Location: kernel/printk/printk.c:2367
Inline: False
Direct callers:
  - kernel/printk/printk.c:unregister_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:resume_console
  - kernel/printk/printk.c:vprintk_emit
  - fs/proc/consoles.c:c_stop
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
  - drivers/video/fbdev/core/fbcon.c:fb_flashcursor
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
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
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:con_install
  - drivers/tty/vt/vt.c:con_write
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
ffffffe00010f20a-ffffffe00010f7d0: console_unlock (STB_GLOBAL)
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
void console_unlock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8110b0a0)
Location: kernel/printk/printk.c:2367
Inline: False
Direct callers:
  - kernel/printk/printk.c:unregister_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:resume_console
  - kernel/printk/printk.c:vprintk_emit
  - fs/proc/consoles.c:c_stop
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:activate
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_rotate
  - drivers/video/fbdev/core/fbcon.c:store_rotate_all
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fb_flashcursor
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
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
ffffffff8110b0a0-ffffffff8110b573: console_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void console_unlock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810fbf20)
Location: kernel/printk/printk.c:2367
Inline: False
Direct callers:
  - kernel/printk/printk.c:unregister_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:resume_console
  - kernel/printk/printk.c:vprintk_emit
  - fs/proc/consoles.c:c_stop
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:activate
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_rotate
  - drivers/video/fbdev/core/fbcon.c:store_rotate_all
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fb_flashcursor
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
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
ffffffff810fbf20-ffffffff810fc3d1: console_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void console_unlock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81108f90)
Location: kernel/printk/printk.c:2367
Inline: False
Direct callers:
  - kernel/printk/printk.c:unregister_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:resume_console
  - kernel/printk/printk.c:vprintk_emit
  - fs/proc/consoles.c:c_stop
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:activate
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_rotate
  - drivers/video/fbdev/core/fbcon.c:store_rotate_all
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fb_flashcursor
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
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
ffffffff81108f90-ffffffff81109463: console_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void console_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff81116c8d)
Location: kernel/printk/printk.c:2367
Inline: True
Inline callers:
  - kernel/printk/printk.c:unregister_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:resume_console
  - kernel/printk/printk.c:vprintk_emit
Direct callers:
  - kernel/printk/printk.c:unregister_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:resume_console
  - kernel/printk/printk.c:vprintk_emit
  - fs/proc/consoles.c:c_stop
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:activate
  - drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:show_rotate
  - drivers/video/fbdev/core/fbcon.c:store_rotate_all
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fbcon_remap_all
  - drivers/video/fbdev/core/fbcon.c:fb_flashcursor
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/vt/vt_ioctl.c:pm_set_vt_switch
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
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
ffffffff811142b0-ffffffff81114763: console_unlock.part.0 (STB_LOCAL)
ffffffff81114770-ffffffff81114791: console_unlock (STB_GLOBAL)
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
