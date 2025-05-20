# Function: <code>fb_set_var</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fb_set_var(struct fb_info *info, struct fb_var_screeninfo *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff8146c3f0)
Location: drivers/video/fbdev/core/fbmem.c:945
Inline: False
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_set_disp
  - drivers/video/console/fbcon.c:fbcon_resize
  - drivers/video/console/fbcon.c:fbcon_blank
  - drivers/video/console/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbsysfs.c:activate
```
**Symbols:**

```
ffffffff8146c3f0-ffffffff8146c850: fb_set_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fb_set_var(struct fb_info *info, struct fb_var_screeninfo *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff814ba740)
Location: drivers/video/fbdev/core/fbmem.c:945
Inline: False
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_blank
  - drivers/video/console/fbcon.c:fbcon_switch
  - drivers/video/console/fbcon.c:fbcon_resize
  - drivers/video/console/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:activate
```
**Symbols:**

```
ffffffff814ba740-ffffffff814bab9f: fb_set_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fb_set_var(struct fb_info *info, struct fb_var_screeninfo *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff814dc740)
Location: drivers/video/fbdev/core/fbmem.c:945
Inline: False
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_blank
  - drivers/video/console/fbcon.c:fbcon_switch
  - drivers/video/console/fbcon.c:fbcon_resize
  - drivers/video/console/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:activate
```
**Symbols:**

```
ffffffff814dc740-ffffffff814dcb9f: fb_set_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fb_set_var(struct fb_info *info, struct fb_var_screeninfo *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff814e8310)
Location: drivers/video/fbdev/core/fbmem.c:945
Inline: False
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_blank
  - drivers/video/console/fbcon.c:fbcon_switch
  - drivers/video/console/fbcon.c:fbcon_resize
  - drivers/video/console/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:activate
```
**Symbols:**

```
ffffffff814e8310-ffffffff814e873b: fb_set_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fb_set_var(struct fb_info *info, struct fb_var_screeninfo *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff8151cdf0)
Location: drivers/video/fbdev/core/fbmem.c:947
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:activate
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
```
**Symbols:**

```
ffffffff8151cdf0-ffffffff8151d227: fb_set_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int fb_set_var(struct fb_info *info, struct fb_var_screeninfo *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (0)
Location: drivers/video/fbdev/core/fbmem.c:935
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:activate
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
```
**Symbols:**

```
ffffffff81554a8d-ffffffff81554ab4: fb_set_var.cold.13 (STB_LOCAL)
ffffffff81552a80-ffffffff81552eab: fb_set_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int fb_set_var(struct fb_info *info, struct fb_var_screeninfo *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (0)
Location: drivers/video/fbdev/core/fbmem.c:964
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:activate
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
```
**Symbols:**

```
ffffffff8156c3ad-ffffffff8156c3d4: fb_set_var.cold.14 (STB_LOCAL)
ffffffff8156a300-ffffffff8156a72b: fb_set_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int fb_set_var(struct fb_info *info, struct fb_var_screeninfo *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (0)
Location: drivers/video/fbdev/core/fbmem.c:953
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:activate
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
```
**Symbols:**

```
ffffffff8159c84d-ffffffff8159c870: fb_set_var.cold (STB_LOCAL)
ffffffff8159aaa0-ffffffff8159ae63: fb_set_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int fb_set_var(struct fb_info *info, struct fb_var_screeninfo *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (0)
Location: drivers/video/fbdev/core/fbmem.c:953
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:activate
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
```
**Symbols:**

```
ffffffff815bdc2d-ffffffff815bdc50: fb_set_var.cold (STB_LOCAL)
ffffffff815bbe80-ffffffff815bc243: fb_set_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int fb_set_var(struct fb_info *info, struct fb_var_screeninfo *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (0)
Location: drivers/video/fbdev/core/fbmem.c:958
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_rotate
  - drivers/video/fbdev/core/fbsysfs.c:store_bpp
  - drivers/video/fbdev/core/fbsysfs.c:store_mode
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
```
**Symbols:**

```
ffffffff81667c6d-ffffffff81667c90: fb_set_var.cold (STB_LOCAL)
ffffffff81665e50-ffffffff8166615b: fb_set_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int fb_set_var(struct fb_info *info, struct fb_var_screeninfo *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (0)
Location: drivers/video/fbdev/core/fbmem.c:958
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_rotate
  - drivers/video/fbdev/core/fbsysfs.c:store_bpp
  - drivers/video/fbdev/core/fbsysfs.c:store_mode
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
```
**Symbols:**

```
ffffffff81bfebbb-ffffffff81bfebde: fb_set_var.cold (STB_LOCAL)
ffffffff81686ab0-ffffffff81686dd2: fb_set_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int fb_set_var(struct fb_info *info, struct fb_var_screeninfo *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (0)
Location: drivers/video/fbdev/core/fbmem.c:958
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_rotate
  - drivers/video/fbdev/core/fbsysfs.c:store_bpp
  - drivers/video/fbdev/core/fbsysfs.c:store_mode
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
```
**Symbols:**

```
ffffffff81bf074a-ffffffff81bf076d: fb_set_var.cold (STB_LOCAL)
ffffffff816697f0-ffffffff81669b9b: fb_set_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fb_set_var(struct fb_info *info, struct fb_var_screeninfo *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (0)
Location: drivers/video/fbdev/core/fbmem.c:958
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_virtual
  - drivers/video/fbdev/core/fbsysfs.c:store_rotate
  - drivers/video/fbdev/core/fbsysfs.c:store_bpp
  - drivers/video/fbdev/core/fbsysfs.c:store_mode
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
```
**Symbols:**

```
ffffffff81cec287-ffffffff81cec2aa: fb_set_var.cold (STB_LOCAL)
ffffffff816dcc90-ffffffff816dd05f: fb_set_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fb_set_var(struct fb_info *info, struct fb_var_screeninfo *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (0)
Location: drivers/video/fbdev/core/fbmem.c:956
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:activate
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
```
**Symbols:**

```
ffffffff81eb3709-ffffffff81eb3752: fb_set_var.cold (STB_LOCAL)
ffffffff81806b20-ffffffff81806f6f: fb_set_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fb_set_var(struct fb_info *info, struct fb_var_screeninfo *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff81935650)
Location: drivers/video/fbdev/core/fbmem.c:958
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:activate
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
```
**Symbols:**

```
ffffffff81935650-ffffffff81935aa4: fb_set_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fb_set_var(struct fb_info *info, struct fb_var_screeninfo *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff81979940)
Location: drivers/video/fbdev/core/fbmem.c:852
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:activate
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
```
**Symbols:**

```
ffffffff81979940-ffffffff81979d94: fb_set_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fb_set_var(struct fb_info *info, struct fb_var_screeninfo *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff819c3ae0)
Location: drivers/video/fbdev/core/fbmem.c:224
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fb_chrdev.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:activate
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
```
**Symbols:**

```
ffffffff819c3ae0-ffffffff819c3f34: fb_set_var (STB_GLOBAL)
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
int fb_set_var(struct fb_info *info, struct fb_var_screeninfo *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffff800010742c90)
Location: drivers/video/fbdev/core/fbmem.c:953
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:activate
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/amba-clcd.c:clcdfb_register
```
**Symbols:**

```
ffff800010742c90-ffff800010742f98: fb_set_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fb_set_var(struct fb_info *info, struct fb_var_screeninfo *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (c08c7514)
Location: drivers/video/fbdev/core/fbmem.c:953
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:activate
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/amba-clcd.c:clcdfb_probe
```
**Symbols:**

```
c08c7514-c08c785c: fb_set_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fb_set_var(struct fb_info *info, struct fb_var_screeninfo *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (c0000000008a3920)
Location: drivers/video/fbdev/core/fbmem.c:953
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:activate
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
```
**Symbols:**

```
c0000000008a3920-c0000000008a3de4: fb_set_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fb_set_var(struct fb_info *info, struct fb_var_screeninfo *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffe0004f39ae)
Location: drivers/video/fbdev/core/fbmem.c:953
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:activate
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
```
**Symbols:**

```
ffffffe0004f39ae-ffffffe0004f3c94: fb_set_var (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int fb_set_var(struct fb_info *info, struct fb_var_screeninfo *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (0)
Location: drivers/video/fbdev/core/fbmem.c:953
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:activate
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
```
**Symbols:**

```
ffffffff815b1d7d-ffffffff815b1da0: fb_set_var.cold (STB_LOCAL)
ffffffff815affd0-ffffffff815b0393: fb_set_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int fb_set_var(struct fb_info *info, struct fb_var_screeninfo *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (0)
Location: drivers/video/fbdev/core/fbmem.c:953
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:activate
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
```
**Symbols:**

```
ffffffff815a0f0d-ffffffff815a0f30: fb_set_var.cold (STB_LOCAL)
ffffffff8159f160-ffffffff8159f523: fb_set_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int fb_set_var(struct fb_info *info, struct fb_var_screeninfo *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (0)
Location: drivers/video/fbdev/core/fbmem.c:953
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:activate
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
```
**Symbols:**

```
ffffffff815b230d-ffffffff815b2330: fb_set_var.cold (STB_LOCAL)
ffffffff815b0560-ffffffff815b0923: fb_set_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int fb_set_var(struct fb_info *info, struct fb_var_screeninfo *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (0)
Location: drivers/video/fbdev/core/fbmem.c:953
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:activate
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
```
**Symbols:**

```
ffffffff815cbd7d-ffffffff815cbda0: fb_set_var.cold (STB_LOCAL)
ffffffff815c9fd0-ffffffff815ca393: fb_set_var (STB_GLOBAL)
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
