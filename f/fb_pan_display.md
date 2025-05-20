# Function: <code>fb_pan_display</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fb_pan_display(struct fb_info *info, struct fb_var_screeninfo *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff8146c0c0)
Location: drivers/video/fbdev/core/fbmem.c:884
Inline: False
Direct callers:
  - drivers/video/console/bitblit.c:bit_update_start
  - drivers/video/console/tileblit.c:tile_update_start
  - drivers/video/console/fbcon_cw.c:cw_update_start
  - drivers/video/console/fbcon_ud.c:ud_update_start
  - drivers/video/console/fbcon_ccw.c:ccw_update_start
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
```
**Symbols:**

```
ffffffff8146c0c0-ffffffff8146c217: fb_pan_display (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fb_pan_display(struct fb_info *info, struct fb_var_screeninfo *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff814ba410)
Location: drivers/video/fbdev/core/fbmem.c:884
Inline: False
Direct callers:
  - drivers/video/console/bitblit.c:bit_update_start
  - drivers/video/console/tileblit.c:tile_update_start
  - drivers/video/console/fbcon_cw.c:cw_update_start
  - drivers/video/console/fbcon_ud.c:ud_update_start
  - drivers/video/console/fbcon_ccw.c:ccw_update_start
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
```
**Symbols:**

```
ffffffff814ba410-ffffffff814ba567: fb_pan_display (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fb_pan_display(struct fb_info *info, struct fb_var_screeninfo *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff814dc410)
Location: drivers/video/fbdev/core/fbmem.c:884
Inline: False
Direct callers:
  - drivers/video/console/bitblit.c:bit_update_start
  - drivers/video/console/tileblit.c:tile_update_start
  - drivers/video/console/fbcon_cw.c:cw_update_start
  - drivers/video/console/fbcon_ud.c:ud_update_start
  - drivers/video/console/fbcon_ccw.c:ccw_update_start
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
```
**Symbols:**

```
ffffffff814dc410-ffffffff814dc567: fb_pan_display (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fb_pan_display(struct fb_info *info, struct fb_var_screeninfo *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff814e7fd0)
Location: drivers/video/fbdev/core/fbmem.c:884
Inline: False
Direct callers:
  - drivers/video/console/bitblit.c:bit_update_start
  - drivers/video/console/tileblit.c:tile_update_start
  - drivers/video/console/fbcon_cw.c:cw_update_start
  - drivers/video/console/fbcon_ud.c:ud_update_start
  - drivers/video/console/fbcon_ccw.c:ccw_update_start
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
```
**Symbols:**

```
ffffffff814e7fd0-ffffffff814e8114: fb_pan_display (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fb_pan_display(struct fb_info *info, struct fb_var_screeninfo *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff8151cad0)
Location: drivers/video/fbdev/core/fbmem.c:886
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/bitblit.c:bit_update_start
  - drivers/video/fbdev/core/tileblit.c:tile_update_start
  - drivers/video/fbdev/core/fbcon_cw.c:cw_update_start
  - drivers/video/fbdev/core/fbcon_ud.c:ud_update_start
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_update_start
```
**Symbols:**

```
ffffffff8151cad0-ffffffff8151cc17: fb_pan_display (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fb_pan_display(struct fb_info *info, struct fb_var_screeninfo *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff81552790)
Location: drivers/video/fbdev/core/fbmem.c:874
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/bitblit.c:bit_update_start
  - drivers/video/fbdev/core/tileblit.c:tile_update_start
  - drivers/video/fbdev/core/fbcon_cw.c:cw_update_start
  - drivers/video/fbdev/core/fbcon_ud.c:ud_update_start
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_update_start
```
**Symbols:**

```
ffffffff81552790-ffffffff815528a3: fb_pan_display (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fb_pan_display(struct fb_info *info, struct fb_var_screeninfo *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff8156a010)
Location: drivers/video/fbdev/core/fbmem.c:903
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/bitblit.c:bit_update_start
  - drivers/video/fbdev/core/tileblit.c:tile_update_start
  - drivers/video/fbdev/core/fbcon_cw.c:cw_update_start
  - drivers/video/fbdev/core/fbcon_ud.c:ud_update_start
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_update_start
```
**Symbols:**

```
ffffffff8156a010-ffffffff8156a125: fb_pan_display (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fb_pan_display(struct fb_info *info, struct fb_var_screeninfo *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff8159a8d0)
Location: drivers/video/fbdev/core/fbmem.c:895
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/bitblit.c:bit_update_start
  - drivers/video/fbdev/core/tileblit.c:tile_update_start
  - drivers/video/fbdev/core/fbcon_cw.c:cw_update_start
  - drivers/video/fbdev/core/fbcon_ud.c:ud_update_start
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_update_start
```
**Symbols:**

```
ffffffff8159a8d0-ffffffff8159a9de: fb_pan_display (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fb_pan_display(struct fb_info *info, struct fb_var_screeninfo *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff815bbcd0)
Location: drivers/video/fbdev/core/fbmem.c:895
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/bitblit.c:bit_update_start
  - drivers/video/fbdev/core/tileblit.c:tile_update_start
  - drivers/video/fbdev/core/fbcon_cw.c:cw_update_start
  - drivers/video/fbdev/core/fbcon_ud.c:ud_update_start
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_update_start
```
**Symbols:**

```
ffffffff815bbcd0-ffffffff815bbdde: fb_pan_display (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fb_pan_display(struct fb_info *info, struct fb_var_screeninfo *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff81665bd0)
Location: drivers/video/fbdev/core/fbmem.c:900
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/bitblit.c:bit_update_start
  - drivers/video/fbdev/core/tileblit.c:tile_update_start
  - drivers/video/fbdev/core/fbcon_cw.c:cw_update_start
  - drivers/video/fbdev/core/fbcon_ud.c:ud_update_start
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_update_start
```
**Symbols:**

```
ffffffff81665bd0-ffffffff81665cde: fb_pan_display (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fb_pan_display(struct fb_info *info, struct fb_var_screeninfo *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff81686850)
Location: drivers/video/fbdev/core/fbmem.c:900
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/bitblit.c:bit_update_start
  - drivers/video/fbdev/core/tileblit.c:tile_update_start
  - drivers/video/fbdev/core/fbcon_cw.c:cw_update_start
  - drivers/video/fbdev/core/fbcon_ud.c:ud_update_start
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_update_start
```
**Symbols:**

```
ffffffff81686850-ffffffff8168695e: fb_pan_display (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fb_pan_display(struct fb_info *info, struct fb_var_screeninfo *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff81669650)
Location: drivers/video/fbdev/core/fbmem.c:900
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/bitblit.c:bit_update_start
  - drivers/video/fbdev/core/tileblit.c:tile_update_start
  - drivers/video/fbdev/core/fbcon_cw.c:cw_update_start
  - drivers/video/fbdev/core/fbcon_ud.c:ud_update_start
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_update_start
```
**Symbols:**

```
ffffffff81669650-ffffffff8166975e: fb_pan_display (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fb_pan_display(struct fb_info *info, struct fb_var_screeninfo *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff816dc9b0)
Location: drivers/video/fbdev/core/fbmem.c:900
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/bitblit.c:bit_update_start
  - drivers/video/fbdev/core/tileblit.c:tile_update_start
  - drivers/video/fbdev/core/fbcon_cw.c:cw_update_start
  - drivers/video/fbdev/core/fbcon_ud.c:ud_update_start
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_update_start
```
**Symbols:**

```
ffffffff816dc9b0-ffffffff816dcabe: fb_pan_display (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fb_pan_display(struct fb_info *info, struct fb_var_screeninfo *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff818067c0)
Location: drivers/video/fbdev/core/fbmem.c:898
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/bitblit.c:bit_update_start
  - drivers/video/fbdev/core/tileblit.c:tile_update_start
  - drivers/video/fbdev/core/fbcon_cw.c:cw_update_start
  - drivers/video/fbdev/core/fbcon_ud.c:ud_update_start
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_update_start
```
**Symbols:**

```
ffffffff818067c0-ffffffff81806910: fb_pan_display (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fb_pan_display(struct fb_info *info, struct fb_var_screeninfo *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff819352c0)
Location: drivers/video/fbdev/core/fbmem.c:900
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/bitblit.c:bit_update_start
  - drivers/video/fbdev/core/tileblit.c:tile_update_start
  - drivers/video/fbdev/core/fbcon_cw.c:cw_update_start
  - drivers/video/fbdev/core/fbcon_ud.c:ud_update_start
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_update_start
```
**Symbols:**

```
ffffffff819352c0-ffffffff81935410: fb_pan_display (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fb_pan_display(struct fb_info *info, struct fb_var_screeninfo *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff819795b0)
Location: drivers/video/fbdev/core/fbmem.c:794
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/bitblit.c:bit_update_start
  - drivers/video/fbdev/core/tileblit.c:tile_update_start
  - drivers/video/fbdev/core/fbcon_cw.c:cw_update_start
  - drivers/video/fbdev/core/fbcon_ud.c:ud_update_start
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_update_start
```
**Symbols:**

```
ffffffff819795b0-ffffffff81979700: fb_pan_display (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fb_pan_display(struct fb_info *info, struct fb_var_screeninfo *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff819c3750)
Location: drivers/video/fbdev/core/fbmem.c:166
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fb_chrdev.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/bitblit.c:bit_update_start
  - drivers/video/fbdev/core/tileblit.c:tile_update_start
  - drivers/video/fbdev/core/fbcon_cw.c:cw_update_start
  - drivers/video/fbdev/core/fbcon_ud.c:ud_update_start
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_update_start
```
**Symbols:**

```
ffffffff819c3750-ffffffff819c38a0: fb_pan_display (STB_GLOBAL)
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
int fb_pan_display(struct fb_info *info, struct fb_var_screeninfo *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffff800010742ad8)
Location: drivers/video/fbdev/core/fbmem.c:895
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/bitblit.c:bit_update_start
  - drivers/video/fbdev/core/tileblit.c:tile_update_start
  - drivers/video/fbdev/core/fbcon_cw.c:cw_update_start
  - drivers/video/fbdev/core/fbcon_ud.c:ud_update_start
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_update_start
```
**Symbols:**

```
ffff800010742ad8-ffff800010742be8: fb_pan_display (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fb_pan_display(struct fb_info *info, struct fb_var_screeninfo *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (c08c7348)
Location: drivers/video/fbdev/core/fbmem.c:895
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/bitblit.c:bit_update_start
  - drivers/video/fbdev/core/tileblit.c:tile_update_start
  - drivers/video/fbdev/core/fbcon_cw.c:cw_update_start
  - drivers/video/fbdev/core/fbcon_ud.c:ud_update_start
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_update_start
```
**Symbols:**

```
c08c7348-c08c7468: fb_pan_display (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fb_pan_display(struct fb_info *info, struct fb_var_screeninfo *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (c0000000008a3660)
Location: drivers/video/fbdev/core/fbmem.c:895
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/bitblit.c:bit_update_start
  - drivers/video/fbdev/core/tileblit.c:tile_update_start
  - drivers/video/fbdev/core/fbcon_cw.c:cw_update_start
  - drivers/video/fbdev/core/fbcon_ud.c:ud_update_start
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_update_start
```
**Symbols:**

```
c0000000008a3660-c0000000008a3830: fb_pan_display (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fb_pan_display(struct fb_info *info, struct fb_var_screeninfo *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffe0004f386c)
Location: drivers/video/fbdev/core/fbmem.c:895
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/bitblit.c:bit_update_start
  - drivers/video/fbdev/core/tileblit.c:tile_update_start
  - drivers/video/fbdev/core/fbcon_cw.c:cw_update_start
  - drivers/video/fbdev/core/fbcon_ud.c:ud_update_start
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_update_start
```
**Symbols:**

```
ffffffe0004f386c-ffffffe0004f393c: fb_pan_display (STB_GLOBAL)
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
int fb_pan_display(struct fb_info *info, struct fb_var_screeninfo *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff815afe20)
Location: drivers/video/fbdev/core/fbmem.c:895
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/bitblit.c:bit_update_start
  - drivers/video/fbdev/core/tileblit.c:tile_update_start
  - drivers/video/fbdev/core/fbcon_cw.c:cw_update_start
  - drivers/video/fbdev/core/fbcon_ud.c:ud_update_start
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_update_start
```
**Symbols:**

```
ffffffff815afe20-ffffffff815aff2e: fb_pan_display (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fb_pan_display(struct fb_info *info, struct fb_var_screeninfo *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff8159efb0)
Location: drivers/video/fbdev/core/fbmem.c:895
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/bitblit.c:bit_update_start
  - drivers/video/fbdev/core/tileblit.c:tile_update_start
  - drivers/video/fbdev/core/fbcon_cw.c:cw_update_start
  - drivers/video/fbdev/core/fbcon_ud.c:ud_update_start
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_update_start
```
**Symbols:**

```
ffffffff8159efb0-ffffffff8159f0be: fb_pan_display (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fb_pan_display(struct fb_info *info, struct fb_var_screeninfo *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff815b03b0)
Location: drivers/video/fbdev/core/fbmem.c:895
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/bitblit.c:bit_update_start
  - drivers/video/fbdev/core/tileblit.c:tile_update_start
  - drivers/video/fbdev/core/fbcon_cw.c:cw_update_start
  - drivers/video/fbdev/core/fbcon_ud.c:ud_update_start
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_update_start
```
**Symbols:**

```
ffffffff815b03b0-ffffffff815b04be: fb_pan_display (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fb_pan_display(struct fb_info *info, struct fb_var_screeninfo *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff815c9e20)
Location: drivers/video/fbdev/core/fbmem.c:895
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
  - drivers/video/fbdev/core/fbsysfs.c:store_pan
  - drivers/video/fbdev/core/bitblit.c:bit_update_start
  - drivers/video/fbdev/core/tileblit.c:tile_update_start
  - drivers/video/fbdev/core/fbcon_cw.c:cw_update_start
  - drivers/video/fbdev/core/fbcon_ud.c:ud_update_start
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_update_start
```
**Symbols:**

```
ffffffff815c9e20-ffffffff815c9f2e: fb_pan_display (STB_GLOBAL)
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
