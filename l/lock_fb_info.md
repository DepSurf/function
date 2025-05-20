# Function: <code>lock_fb_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int lock_fb_info(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff8146c250)
Location: drivers/video/fbdev/core/fbmem.c:77
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
**Symbols:**

```
ffffffff8146c250-ffffffff8146c28e: lock_fb_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int lock_fb_info(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff814bc176)
Location: drivers/video/fbdev/core/fbmem.c:77
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
**Symbols:**

```
ffffffff814ba5a0-ffffffff814ba5de: lock_fb_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int lock_fb_info(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff814de176)
Location: drivers/video/fbdev/core/fbmem.c:77
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
**Symbols:**

```
ffffffff814dc5a0-ffffffff814dc5de: lock_fb_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int lock_fb_info(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff814e975d)
Location: drivers/video/fbdev/core/fbmem.c:77
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
**Symbols:**

```
ffffffff814e8150-ffffffff814e818e: lock_fb_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int lock_fb_info(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff8151e29d)
Location: drivers/video/fbdev/core/fbmem.c:79
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
Direct callers:
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
```
**Symbols:**

```
ffffffff8151cc50-ffffffff8151cc8e: lock_fb_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int lock_fb_info(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff81553e61)
Location: drivers/video/fbdev/core/fbmem.c:79
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:unbind_console
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
Direct callers:
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
```
**Symbols:**

```
ffffffff815528e0-ffffffff8155291b: lock_fb_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int lock_fb_info(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff8156b648)
Location: drivers/video/fbdev/core/fbmem.c:83
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:unbind_console
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
Direct callers:
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
```
**Symbols:**

```
ffffffff8156a160-ffffffff8156a19b: lock_fb_info (STB_GLOBAL)
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
In drivers/video/fbdev/core/fbmem.c (ffffffff8159bb27)
Location: include/linux/fb.h:639
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
  - drivers/video/fbdev/core/fbmem.c:fb_release
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
```
```
In drivers/video/fbdev/core/fbcmap.c (ffffffff8159f797)
Location: include/linux/fb.h:639
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff8159fb3f)
Location: include/linux/fb.h:639
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
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
In drivers/video/fbdev/core/fbmem.c (ffffffff815bd127)
Location: include/linux/fb.h:635
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
  - drivers/video/fbdev/core/fbmem.c:fb_release
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
```
```
In drivers/video/fbdev/core/fbcmap.c (ffffffff815c0617)
Location: include/linux/fb.h:635
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff815c09bf)
Location: include/linux/fb.h:635
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
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
In drivers/video/fbdev/core/fbmem.c (ffffffff81666ccf)
Location: include/linux/fb.h:633
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:fb_release
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
```
```
In drivers/video/fbdev/core/fbcmap.c (ffffffff8166a8e7)
Location: include/linux/fb.h:633
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff8166ac8f)
Location: include/linux/fb.h:633
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
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
In drivers/video/fbdev/core/fbmem.c (ffffffff816878af)
Location: include/linux/fb.h:634
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:fb_release
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
```
```
In drivers/video/fbdev/core/fbcmap.c (ffffffff8168b257)
Location: include/linux/fb.h:634
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff8168b5df)
Location: include/linux/fb.h:634
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff8166a51f)
Location: include/linux/fb.h:634
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:fb_release
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
```
```
In drivers/video/fbdev/core/fbcmap.c (ffffffff8166df37)
Location: include/linux/fb.h:634
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff8166e2c0)
Location: include/linux/fb.h:634
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff816de3d0)
Location: include/linux/fb.h:636
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:fb_release
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
```
```
In drivers/video/fbdev/core/fbcmap.c (ffffffff816e1de7)
Location: include/linux/fb.h:636
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff816e2490)
Location: include/linux/fb.h:636
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff81808ac3)
Location: include/linux/fb.h:645
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_release
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
```
```
In drivers/video/fbdev/core/fbcmap.c (ffffffff8180c02b)
Location: include/linux/fb.h:645
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff8180c7fd)
Location: include/linux/fb.h:645
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:activate
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff81810866)
Location: include/linux/fb.h:645
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_open
  - drivers/video/fbdev/core/fbcon.c:fbcon_release
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff81937413)
Location: include/linux/fb.h:640
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_release
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
```
```
In drivers/video/fbdev/core/fbcmap.c (ffffffff8193a9db)
Location: include/linux/fb.h:640
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff8193b21d)
Location: include/linux/fb.h:640
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:activate
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff8193f686)
Location: include/linux/fb.h:640
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_open
  - drivers/video/fbdev/core/fbcon.c:fbcon_release
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff8197b4b3)
Location: include/linux/fb.h:620
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_release
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
```
```
In drivers/video/fbdev/core/fbcmap.c (ffffffff8197e9db)
Location: include/linux/fb.h:620
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff8197f21d)
Location: include/linux/fb.h:620
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:activate
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff81983b96)
Location: include/linux/fb.h:620
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_open
  - drivers/video/fbdev/core/fbcon.c:fbcon_release
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcmap.c (ffffffff819c53ab)
Location: include/linux/fb.h:605
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
```
```
In drivers/video/fbdev/core/fb_chrdev.c (ffffffff819ca0e3)
Location: include/linux/fb.h:605
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_chrdev.c:fb_release
  - drivers/video/fbdev/core/fb_chrdev.c:fb_open
  - drivers/video/fbdev/core/fb_chrdev.c:fb_getput_cmap
  - drivers/video/fbdev/core/fb_chrdev.c:do_fb_ioctl
  - drivers/video/fbdev/core/fb_chrdev.c:do_fb_ioctl
  - drivers/video/fbdev/core/fb_chrdev.c:do_fb_ioctl
  - drivers/video/fbdev/core/fb_chrdev.c:do_fb_ioctl
  - drivers/video/fbdev/core/fb_chrdev.c:do_fb_ioctl
  - drivers/video/fbdev/core/fb_chrdev.c:do_fb_ioctl
  - drivers/video/fbdev/core/fb_chrdev.c:do_fb_ioctl
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff819cb98d)
Location: include/linux/fb.h:605
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:activate
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff819cd7a6)
Location: include/linux/fb.h:605
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_open
  - drivers/video/fbdev/core/fbcon.c:fbcon_release
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
In drivers/video/fbdev/core/fbmem.c (ffff800010743e00)
Location: include/linux/fb.h:635
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
  - drivers/video/fbdev/core/fbmem.c:fb_release
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
```
```
In drivers/video/fbdev/core/fbcmap.c (ffff8000107493b4)
Location: include/linux/fb.h:635
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffff800010749764)
Location: include/linux/fb.h:635
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
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
In drivers/video/fbdev/core/fbmem.c (c08c8024)
Location: include/linux/fb.h:635
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
  - drivers/video/fbdev/core/fbmem.c:fb_release
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
```
```
In drivers/video/fbdev/core/fbcmap.c (c08cbed0)
Location: include/linux/fb.h:635
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
```
```
In drivers/video/fbdev/core/fbsysfs.c (c08cc254)
Location: include/linux/fb.h:635
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
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
In drivers/video/fbdev/core/fbmem.c (c0000000008a5178)
Location: include/linux/fb.h:635
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
  - drivers/video/fbdev/core/fbmem.c:fb_release
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
```
```
In drivers/video/fbdev/core/fbcmap.c (c0000000008aa570)
Location: include/linux/fb.h:635
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
```
```
In drivers/video/fbdev/core/fbsysfs.c (c0000000008aaa50)
Location: include/linux/fb.h:635
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
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
In drivers/video/fbdev/core/fbmem.c (ffffffe0004f4874)
Location: include/linux/fb.h:635
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
  - drivers/video/fbdev/core/fbmem.c:fb_release
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
```
```
In drivers/video/fbdev/core/fbcmap.c (ffffffe0004f783e)
Location: include/linux/fb.h:635
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffe0004f7b6e)
Location: include/linux/fb.h:635
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
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
In drivers/video/fbdev/core/fbmem.c (ffffffff815b1277)
Location: include/linux/fb.h:635
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
  - drivers/video/fbdev/core/fbmem.c:fb_release
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
```
```
In drivers/video/fbdev/core/fbcmap.c (ffffffff815b4767)
Location: include/linux/fb.h:635
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff815b4b0f)
Location: include/linux/fb.h:635
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
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
In drivers/video/fbdev/core/fbmem.c (ffffffff815a0407)
Location: include/linux/fb.h:635
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
  - drivers/video/fbdev/core/fbmem.c:fb_release
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
```
```
In drivers/video/fbdev/core/fbcmap.c (ffffffff815a3807)
Location: include/linux/fb.h:635
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff815a390f)
Location: include/linux/fb.h:635
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
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
In drivers/video/fbdev/core/fbmem.c (ffffffff815b1807)
Location: include/linux/fb.h:635
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
  - drivers/video/fbdev/core/fbmem.c:fb_release
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
```
```
In drivers/video/fbdev/core/fbcmap.c (ffffffff815b4cf7)
Location: include/linux/fb.h:635
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff815b509f)
Location: include/linux/fb.h:635
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
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
In drivers/video/fbdev/core/fbmem.c (ffffffff815cb277)
Location: include/linux/fb.h:635
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
  - drivers/video/fbdev/core/fbmem.c:fb_release
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
```
```
In drivers/video/fbdev/core/fbcmap.c (ffffffff815ce767)
Location: include/linux/fb.h:635
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff815ceb0f)
Location: include/linux/fb.h:635
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
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
</ul>
