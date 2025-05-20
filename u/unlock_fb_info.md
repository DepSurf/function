# Function: <code>unlock_fb_info</code>

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
In drivers/video/console/fbcon.c (ffffffff81462823)
Location: include/linux/fb.h:640
Inline: True
Inline callers:
  - drivers/video/console/fbcon.c:fbcon_blank
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8146cadb)
Location: include/linux/fb.h:640
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
```
```
In drivers/video/fbdev/core/fbcmap.c (ffffffff81470faf)
Location: include/linux/fb.h:640
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff81471303)
Location: include/linux/fb.h:640
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
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
In drivers/video/console/fbcon.c (ffffffff814b0823)
Location: include/linux/fb.h:655
Inline: True
Inline callers:
  - drivers/video/console/fbcon.c:fbcon_blank
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff814bc196)
Location: include/linux/fb.h:655
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
```
```
In drivers/video/fbdev/core/fbcmap.c (ffffffff814bf441)
Location: include/linux/fb.h:655
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff814bf7a3)
Location: include/linux/fb.h:655
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
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
In drivers/video/console/fbcon.c (ffffffff814d2933)
Location: include/linux/fb.h:655
Inline: True
Inline callers:
  - drivers/video/console/fbcon.c:fbcon_blank
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff814de196)
Location: include/linux/fb.h:655
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
```
```
In drivers/video/fbdev/core/fbcmap.c (ffffffff814e1431)
Location: include/linux/fb.h:655
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff814e1793)
Location: include/linux/fb.h:655
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
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
In drivers/video/console/fbcon.c (ffffffff814dff79)
Location: include/linux/fb.h:655
Inline: True
Inline callers:
  - drivers/video/console/fbcon.c:fbcon_blank
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff814e977d)
Location: include/linux/fb.h:655
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
```
```
In drivers/video/fbdev/core/fbcmap.c (ffffffff814ed136)
Location: include/linux/fb.h:655
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff814ed473)
Location: include/linux/fb.h:655
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
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
In drivers/video/fbdev/core/fbmem.c (ffffffff8151e2bd)
Location: include/linux/fb.h:648
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
```
```
In drivers/video/fbdev/core/fbcmap.c (ffffffff81521cb6)
Location: include/linux/fb.h:648
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff81521ff3)
Location: include/linux/fb.h:648
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff815282b9)
Location: include/linux/fb.h:648
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
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
In drivers/video/fbdev/core/fbmem.c (ffffffff81553e85)
Location: include/linux/fb.h:655
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
```
```
In drivers/video/fbdev/core/fbcmap.c (ffffffff8155790c)
Location: include/linux/fb.h:655
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff81557c63)
Location: include/linux/fb.h:655
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff8155ec7d)
Location: include/linux/fb.h:655
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
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
In drivers/video/fbdev/core/fbmem.c (ffffffff8156b66c)
Location: include/linux/fb.h:665
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
```
```
In drivers/video/fbdev/core/fbcmap.c (ffffffff8156f29c)
Location: include/linux/fb.h:665
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff8156f5f3)
Location: include/linux/fb.h:665
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff81575628)
Location: include/linux/fb.h:665
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
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
In drivers/video/fbdev/core/fbmem.c (ffffffff8159bb3d)
Location: include/linux/fb.h:644
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
In drivers/video/fbdev/core/fbcmap.c (ffffffff8159f7ae)
Location: include/linux/fb.h:644
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff8159fb51)
Location: include/linux/fb.h:644
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
In drivers/video/fbdev/core/fbmem.c (ffffffff815bd13d)
Location: include/linux/fb.h:640
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
In drivers/video/fbdev/core/fbcmap.c (ffffffff815c062e)
Location: include/linux/fb.h:640
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff815c09d1)
Location: include/linux/fb.h:640
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
In drivers/video/fbdev/core/fbmem.c (ffffffff81666ce4)
Location: include/linux/fb.h:638
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
In drivers/video/fbdev/core/fbcmap.c (ffffffff8166a8fe)
Location: include/linux/fb.h:638
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff8166aca1)
Location: include/linux/fb.h:638
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
In drivers/video/fbdev/core/fbmem.c (ffffffff816878c4)
Location: include/linux/fb.h:639
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
In drivers/video/fbdev/core/fbcmap.c (ffffffff8168b26e)
Location: include/linux/fb.h:639
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff8168b5f1)
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
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff8166a534)
Location: include/linux/fb.h:639
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
In drivers/video/fbdev/core/fbcmap.c (ffffffff8166df4e)
Location: include/linux/fb.h:639
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff8166e2d2)
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
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff816de3e5)
Location: include/linux/fb.h:641
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
In drivers/video/fbdev/core/fbcmap.c (ffffffff816e1dfe)
Location: include/linux/fb.h:641
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff816e24a2)
Location: include/linux/fb.h:641
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
In drivers/video/fbdev/core/fbmem.c (ffffffff81808afb)
Location: include/linux/fb.h:650
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
In drivers/video/fbdev/core/fbcmap.c (ffffffff8180c042)
Location: include/linux/fb.h:650
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff8180c80f)
Location: include/linux/fb.h:650
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:activate
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff81810896)
Location: include/linux/fb.h:650
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_open
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
In drivers/video/fbdev/core/fbmem.c (ffffffff8193745d)
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
In drivers/video/fbdev/core/fbcmap.c (ffffffff8193a9f2)
Location: include/linux/fb.h:645
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff8193b22f)
Location: include/linux/fb.h:645
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:activate
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff8193f6b6)
Location: include/linux/fb.h:645
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_open
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
In drivers/video/fbdev/core/fbmem.c (ffffffff8197b4fd)
Location: include/linux/fb.h:625
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
In drivers/video/fbdev/core/fbcmap.c (ffffffff8197e9f2)
Location: include/linux/fb.h:625
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff8197f22f)
Location: include/linux/fb.h:625
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:activate
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff81983bc6)
Location: include/linux/fb.h:625
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_open
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
In drivers/video/fbdev/core/fbcmap.c (ffffffff819c53c2)
Location: include/linux/fb.h:610
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
```
```
In drivers/video/fbdev/core/fb_chrdev.c (ffffffff819ca12d)
Location: include/linux/fb.h:610
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
In drivers/video/fbdev/core/fbsysfs.c (ffffffff819cb99f)
Location: include/linux/fb.h:610
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:activate
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff819cd7d6)
Location: include/linux/fb.h:610
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_open
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
In drivers/video/fbdev/core/fbmem.c (ffff800010743e18)
Location: include/linux/fb.h:640
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
In drivers/video/fbdev/core/fbcmap.c (ffff8000107493cc)
Location: include/linux/fb.h:640
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffff800010749778)
Location: include/linux/fb.h:640
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
In drivers/video/fbdev/core/fbmem.c (c08c803c)
Location: include/linux/fb.h:640
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
In drivers/video/fbdev/core/fbcmap.c (c08cbee8)
Location: include/linux/fb.h:640
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
```
```
In drivers/video/fbdev/core/fbsysfs.c (c08cc268)
Location: include/linux/fb.h:640
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
In drivers/video/fbdev/core/fbmem.c (c0000000008a5198)
Location: include/linux/fb.h:640
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
In drivers/video/fbdev/core/fbcmap.c (c0000000008aa58c)
Location: include/linux/fb.h:640
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
```
```
In drivers/video/fbdev/core/fbsysfs.c (c0000000008aaa6c)
Location: include/linux/fb.h:640
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
In drivers/video/fbdev/core/fbmem.c (ffffffe0004f488a)
Location: include/linux/fb.h:640
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
In drivers/video/fbdev/core/fbcmap.c (ffffffe0004f7860)
Location: include/linux/fb.h:640
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffe0004f7b92)
Location: include/linux/fb.h:640
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
In drivers/video/fbdev/core/fbmem.c (ffffffff815b128d)
Location: include/linux/fb.h:640
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
In drivers/video/fbdev/core/fbcmap.c (ffffffff815b477e)
Location: include/linux/fb.h:640
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff815b4b21)
Location: include/linux/fb.h:640
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
In drivers/video/fbdev/core/fbmem.c (ffffffff815a041d)
Location: include/linux/fb.h:640
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
In drivers/video/fbdev/core/fbcmap.c (ffffffff815a381e)
Location: include/linux/fb.h:640
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff815a3921)
Location: include/linux/fb.h:640
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
In drivers/video/fbdev/core/fbmem.c (ffffffff815b181d)
Location: include/linux/fb.h:640
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
In drivers/video/fbdev/core/fbcmap.c (ffffffff815b4d0e)
Location: include/linux/fb.h:640
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff815b50b1)
Location: include/linux/fb.h:640
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
In drivers/video/fbdev/core/fbmem.c (ffffffff815cb28d)
Location: include/linux/fb.h:640
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
In drivers/video/fbdev/core/fbcmap.c (ffffffff815ce77e)
Location: include/linux/fb.h:640
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff815ceb21)
Location: include/linux/fb.h:640
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_fbstate
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
</details>
</li>
</ul>

## Differences
