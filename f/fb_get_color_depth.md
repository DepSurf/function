# Function: <code>fb_get_color_depth</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fb_get_color_depth(struct fb_var_screeninfo *var, struct fb_fix_screeninfo *fix);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff8146be50)
Location: drivers/video/fbdev/core/fbmem.c:92
Inline: False
Direct callers:
  - drivers/video/console/fbcon.c:get_color
  - drivers/video/console/fbcon.c:fbcon_set_palette
  - drivers/video/console/fbcon.c:fbcon_set_disp
  - drivers/video/console/fbcon.c:fbcon_prepare_logo
  - drivers/video/console/fbcon.c:fbcon_switch
  - drivers/video/console/fbcon.c:fbcon_init
  - drivers/video/console/fbcon.c:fbcon_init
  - drivers/video/console/bitblit.c:bit_cursor
  - drivers/video/console/bitblit.c:bit_putcs
  - drivers/video/console/fbcon_cw.c:cw_cursor
  - drivers/video/console/fbcon_cw.c:cw_putcs
  - drivers/video/console/fbcon_ud.c:ud_cursor
  - drivers/video/console/fbcon_ud.c:ud_putcs
  - drivers/video/console/fbcon_ccw.c:ccw_cursor
  - drivers/video/console/fbcon_ccw.c:ccw_putcs
```
**Symbols:**

```
ffffffff8146be50-ffffffff8146be8e: fb_get_color_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fb_get_color_depth(struct fb_var_screeninfo *var, struct fb_fix_screeninfo *fix);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff814ba1a0)
Location: drivers/video/fbdev/core/fbmem.c:92
Inline: False
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_set_palette
  - drivers/video/console/fbcon.c:fbcon_switch
  - drivers/video/console/fbcon.c:fbcon_set_disp
  - drivers/video/console/fbcon.c:fbcon_init
  - drivers/video/console/fbcon.c:fbcon_init
  - drivers/video/console/fbcon.c:fbcon_prepare_logo
  - drivers/video/console/fbcon.c:get_color
  - drivers/video/console/bitblit.c:bit_cursor
  - drivers/video/console/bitblit.c:bit_putcs
  - drivers/video/console/fbcon_cw.c:cw_cursor
  - drivers/video/console/fbcon_cw.c:cw_putcs
  - drivers/video/console/fbcon_ud.c:ud_cursor
  - drivers/video/console/fbcon_ud.c:ud_putcs
  - drivers/video/console/fbcon_ccw.c:ccw_cursor
  - drivers/video/console/fbcon_ccw.c:ccw_putcs
```
**Symbols:**

```
ffffffff814ba1a0-ffffffff814ba1e1: fb_get_color_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fb_get_color_depth(struct fb_var_screeninfo *var, struct fb_fix_screeninfo *fix);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff814dc1a0)
Location: drivers/video/fbdev/core/fbmem.c:92
Inline: False
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_set_palette
  - drivers/video/console/fbcon.c:fbcon_switch
  - drivers/video/console/fbcon.c:fbcon_set_disp
  - drivers/video/console/fbcon.c:fbcon_init
  - drivers/video/console/fbcon.c:fbcon_init
  - drivers/video/console/fbcon.c:fbcon_prepare_logo
  - drivers/video/console/fbcon.c:get_color
  - drivers/video/console/bitblit.c:bit_cursor
  - drivers/video/console/bitblit.c:bit_putcs
  - drivers/video/console/fbcon_cw.c:cw_cursor
  - drivers/video/console/fbcon_cw.c:cw_putcs
  - drivers/video/console/fbcon_ud.c:ud_cursor
  - drivers/video/console/fbcon_ud.c:ud_putcs
  - drivers/video/console/fbcon_ccw.c:ccw_cursor
  - drivers/video/console/fbcon_ccw.c:ccw_putcs
```
**Symbols:**

```
ffffffff814dc1a0-ffffffff814dc1e1: fb_get_color_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int fb_get_color_depth(struct fb_var_screeninfo *var, struct fb_fix_screeninfo *fix);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff814e9930)
Location: drivers/video/fbdev/core/fbmem.c:92
Inline: True
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_set_palette
  - drivers/video/console/fbcon.c:fbcon_switch
  - drivers/video/console/fbcon.c:fbcon_set_disp
  - drivers/video/console/fbcon.c:fbcon_init
  - drivers/video/console/fbcon.c:fbcon_init
  - drivers/video/console/fbcon.c:fbcon_init
  - drivers/video/console/fbcon.c:fbcon_prepare_logo
  - drivers/video/console/fbcon.c:get_color
  - drivers/video/console/bitblit.c:bit_cursor
  - drivers/video/console/bitblit.c:bit_putcs
  - drivers/video/console/fbcon_cw.c:cw_cursor
  - drivers/video/console/fbcon_cw.c:cw_putcs
  - drivers/video/console/fbcon_ud.c:ud_cursor
  - drivers/video/console/fbcon_ud.c:ud_putcs
  - drivers/video/console/fbcon_ccw.c:ccw_cursor
  - drivers/video/console/fbcon_ccw.c:ccw_putcs
```
**Symbols:**

```
ffffffff814e9930-ffffffff814e996a: fb_get_color_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int fb_get_color_depth(struct fb_var_screeninfo *var, struct fb_fix_screeninfo *fix);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff8151e480)
Location: drivers/video/fbdev/core/fbmem.c:94
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_palette
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:get_color
  - drivers/video/fbdev/core/bitblit.c:bit_cursor
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
  - drivers/video/fbdev/core/fbcon_cw.c:cw_cursor
  - drivers/video/fbdev/core/fbcon_cw.c:cw_putcs
  - drivers/video/fbdev/core/fbcon_ud.c:ud_cursor
  - drivers/video/fbdev/core/fbcon_ud.c:ud_putcs
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_cursor
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_putcs
```
**Symbols:**

```
ffffffff8151e480-ffffffff8151e4ba: fb_get_color_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int fb_get_color_depth(struct fb_var_screeninfo *var, struct fb_fix_screeninfo *fix);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff81554030)
Location: drivers/video/fbdev/core/fbmem.c:94
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_palette
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:get_color
  - drivers/video/fbdev/core/bitblit.c:bit_cursor
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
  - drivers/video/fbdev/core/fbcon_cw.c:cw_cursor
  - drivers/video/fbdev/core/fbcon_cw.c:cw_putcs
  - drivers/video/fbdev/core/fbcon_ud.c:ud_cursor
  - drivers/video/fbdev/core/fbcon_ud.c:ud_putcs
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_cursor
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_putcs
```
**Symbols:**

```
ffffffff81554030-ffffffff8155406a: fb_get_color_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int fb_get_color_depth(struct fb_var_screeninfo *var, struct fb_fix_screeninfo *fix);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff8156b810)
Location: drivers/video/fbdev/core/fbmem.c:98
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_palette
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:get_color
  - drivers/video/fbdev/core/bitblit.c:bit_cursor
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
  - drivers/video/fbdev/core/fbcon_cw.c:cw_cursor
  - drivers/video/fbdev/core/fbcon_cw.c:cw_putcs
  - drivers/video/fbdev/core/fbcon_ud.c:ud_cursor
  - drivers/video/fbdev/core/fbcon_ud.c:ud_putcs
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_cursor
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_putcs
```
**Symbols:**

```
ffffffff8156b810-ffffffff8156b84a: fb_get_color_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int fb_get_color_depth(struct fb_var_screeninfo *var, struct fb_fix_screeninfo *fix);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff8159bcf0)
Location: drivers/video/fbdev/core/fbmem.c:87
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_palette
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:get_color
  - drivers/video/fbdev/core/bitblit.c:bit_cursor
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
  - drivers/video/fbdev/core/fbcon_cw.c:cw_cursor
  - drivers/video/fbdev/core/fbcon_cw.c:cw_putcs
  - drivers/video/fbdev/core/fbcon_ud.c:ud_cursor
  - drivers/video/fbdev/core/fbcon_ud.c:ud_putcs
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_cursor
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_putcs
```
**Symbols:**

```
ffffffff8159bcf0-ffffffff8159bd2a: fb_get_color_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int fb_get_color_depth(struct fb_var_screeninfo *var, struct fb_fix_screeninfo *fix);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff815bd2f0)
Location: drivers/video/fbdev/core/fbmem.c:87
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_palette
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:get_color
  - drivers/video/fbdev/core/bitblit.c:bit_cursor
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
  - drivers/video/fbdev/core/fbcon_cw.c:cw_cursor
  - drivers/video/fbdev/core/fbcon_cw.c:cw_putcs
  - drivers/video/fbdev/core/fbcon_ud.c:ud_cursor
  - drivers/video/fbdev/core/fbcon_ud.c:ud_putcs
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_cursor
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_putcs
```
**Symbols:**

```
ffffffff815bd2f0-ffffffff815bd32a: fb_get_color_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int fb_get_color_depth(struct fb_var_screeninfo *var, struct fb_fix_screeninfo *fix);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff81667190)
Location: drivers/video/fbdev/core/fbmem.c:88
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_palette
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:get_color
  - drivers/video/fbdev/core/bitblit.c:bit_cursor
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
  - drivers/video/fbdev/core/fbcon_cw.c:cw_cursor
  - drivers/video/fbdev/core/fbcon_cw.c:cw_putcs
  - drivers/video/fbdev/core/fbcon_ud.c:ud_cursor
  - drivers/video/fbdev/core/fbcon_ud.c:ud_putcs
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_cursor
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_putcs
```
**Symbols:**

```
ffffffff81667190-ffffffff816671ca: fb_get_color_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int fb_get_color_depth(struct fb_var_screeninfo *var, struct fb_fix_screeninfo *fix);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff81687d70)
Location: drivers/video/fbdev/core/fbmem.c:88
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_palette
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:get_color
  - drivers/video/fbdev/core/bitblit.c:bit_cursor
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
  - drivers/video/fbdev/core/fbcon_cw.c:cw_cursor
  - drivers/video/fbdev/core/fbcon_cw.c:cw_putcs
  - drivers/video/fbdev/core/fbcon_ud.c:ud_cursor
  - drivers/video/fbdev/core/fbcon_ud.c:ud_putcs
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_cursor
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_putcs
```
**Symbols:**

```
ffffffff81687d70-ffffffff81687daa: fb_get_color_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int fb_get_color_depth(struct fb_var_screeninfo *var, struct fb_fix_screeninfo *fix);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff8166a9e0)
Location: drivers/video/fbdev/core/fbmem.c:88
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_palette
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:get_color
  - drivers/video/fbdev/core/bitblit.c:bit_cursor
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
  - drivers/video/fbdev/core/fbcon_cw.c:cw_cursor
  - drivers/video/fbdev/core/fbcon_cw.c:cw_putcs
  - drivers/video/fbdev/core/fbcon_ud.c:ud_cursor
  - drivers/video/fbdev/core/fbcon_ud.c:ud_putcs
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_cursor
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_putcs
```
**Symbols:**

```
ffffffff8166a9e0-ffffffff8166aa1a: fb_get_color_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int fb_get_color_depth(struct fb_var_screeninfo *var, struct fb_fix_screeninfo *fix);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff816ddba0)
Location: drivers/video/fbdev/core/fbmem.c:88
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_palette
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:get_color
  - drivers/video/fbdev/core/bitblit.c:bit_cursor
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
  - drivers/video/fbdev/core/fbcon_cw.c:cw_cursor
  - drivers/video/fbdev/core/fbcon_cw.c:cw_putcs
  - drivers/video/fbdev/core/fbcon_ud.c:ud_cursor
  - drivers/video/fbdev/core/fbcon_ud.c:ud_putcs
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_cursor
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_putcs
```
**Symbols:**

```
ffffffff816ddba0-ffffffff816ddbda: fb_get_color_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int fb_get_color_depth(struct fb_var_screeninfo *var, struct fb_fix_screeninfo *fix);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff81807be0)
Location: drivers/video/fbdev/core/fbmem.c:90
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_palette
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:get_color
  - drivers/video/fbdev/core/bitblit.c:bit_cursor
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
  - drivers/video/fbdev/core/fbcon_cw.c:cw_cursor
  - drivers/video/fbdev/core/fbcon_cw.c:cw_putcs
  - drivers/video/fbdev/core/fbcon_ud.c:ud_cursor
  - drivers/video/fbdev/core/fbcon_ud.c:ud_putcs
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_cursor
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_putcs
```
**Symbols:**

```
ffffffff81807be0-ffffffff81807c26: fb_get_color_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int fb_get_color_depth(struct fb_var_screeninfo *var, struct fb_fix_screeninfo *fix);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff81936b40)
Location: drivers/video/fbdev/core/fbmem.c:92
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_palette
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:get_color
  - drivers/video/fbdev/core/bitblit.c:bit_cursor
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
  - drivers/video/fbdev/core/fbcon_cw.c:cw_cursor
  - drivers/video/fbdev/core/fbcon_cw.c:cw_putcs
  - drivers/video/fbdev/core/fbcon_ud.c:ud_cursor
  - drivers/video/fbdev/core/fbcon_ud.c:ud_putcs
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_cursor
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_putcs
```
**Symbols:**

```
ffffffff81936b40-ffffffff81936b86: fb_get_color_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int fb_get_color_depth(struct fb_var_screeninfo *var, struct fb_fix_screeninfo *fix);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff8197add0)
Location: drivers/video/fbdev/core/fbmem.c:89
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_palette
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:get_color
  - drivers/video/fbdev/core/bitblit.c:bit_cursor
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
  - drivers/video/fbdev/core/fbcon_cw.c:cw_cursor
  - drivers/video/fbdev/core/fbcon_cw.c:cw_putcs
  - drivers/video/fbdev/core/fbcon_ud.c:ud_cursor
  - drivers/video/fbdev/core/fbcon_ud.c:ud_putcs
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_cursor
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_putcs
```
**Symbols:**

```
ffffffff8197add0-ffffffff8197ae24: fb_get_color_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int fb_get_color_depth(struct fb_var_screeninfo *var, struct fb_fix_screeninfo *fix);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff819c4300)
Location: drivers/video/fbdev/core/fbmem.c:66
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_palette
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:get_color
  - drivers/video/fbdev/core/bitblit.c:bit_cursor
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
  - drivers/video/fbdev/core/fbcon_cw.c:cw_cursor
  - drivers/video/fbdev/core/fbcon_cw.c:cw_putcs
  - drivers/video/fbdev/core/fbcon_ud.c:ud_cursor
  - drivers/video/fbdev/core/fbcon_ud.c:ud_putcs
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_cursor
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_putcs
```
**Symbols:**

```
ffffffff819c4300-ffffffff819c4354: fb_get_color_depth (STB_GLOBAL)
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
int fb_get_color_depth(struct fb_var_screeninfo *var, struct fb_fix_screeninfo *fix);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffff8000107432f0)
Location: drivers/video/fbdev/core/fbmem.c:87
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_palette
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/bitblit.c:bit_cursor
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
  - drivers/video/fbdev/core/fbcon_cw.c:cw_cursor
  - drivers/video/fbdev/core/fbcon_cw.c:cw_putcs
  - drivers/video/fbdev/core/fbcon_ud.c:ud_cursor
  - drivers/video/fbdev/core/fbcon_ud.c:ud_putcs
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_cursor
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_putcs
```
**Symbols:**

```
ffff8000107432f0-ffff80001074337c: fb_get_color_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int fb_get_color_depth(struct fb_var_screeninfo *var, struct fb_fix_screeninfo *fix);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (c08c81ac)
Location: drivers/video/fbdev/core/fbmem.c:87
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_palette
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:get_color
  - drivers/video/fbdev/core/bitblit.c:bit_cursor
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
  - drivers/video/fbdev/core/fbcon_cw.c:cw_cursor
  - drivers/video/fbdev/core/fbcon_cw.c:cw_putcs
  - drivers/video/fbdev/core/fbcon_ud.c:ud_cursor
  - drivers/video/fbdev/core/fbcon_ud.c:ud_putcs
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_cursor
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_putcs
```
**Symbols:**

```
c08c81ac-c08c8220: fb_get_color_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int fb_get_color_depth(struct fb_var_screeninfo *var, struct fb_fix_screeninfo *fix);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (c0000000008a5470)
Location: drivers/video/fbdev/core/fbmem.c:87
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_palette
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:get_color
  - drivers/video/fbdev/core/bitblit.c:bit_cursor
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
  - drivers/video/fbdev/core/fbcon_cw.c:cw_cursor
  - drivers/video/fbdev/core/fbcon_cw.c:cw_putcs
  - drivers/video/fbdev/core/fbcon_ud.c:ud_cursor
  - drivers/video/fbdev/core/fbcon_ud.c:ud_putcs
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_cursor
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_putcs
```
**Symbols:**

```
c0000000008a5470-c0000000008a54e8: fb_get_color_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int fb_get_color_depth(struct fb_var_screeninfo *var, struct fb_fix_screeninfo *fix);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffe0004f4a1c)
Location: drivers/video/fbdev/core/fbmem.c:87
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_palette
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:get_color
  - drivers/video/fbdev/core/bitblit.c:bit_cursor
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
  - drivers/video/fbdev/core/fbcon_cw.c:cw_cursor
  - drivers/video/fbdev/core/fbcon_cw.c:cw_putcs
  - drivers/video/fbdev/core/fbcon_ud.c:ud_cursor
  - drivers/video/fbdev/core/fbcon_ud.c:ud_putcs
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_cursor
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_putcs
```
**Symbols:**

```
ffffffe0004f4a1c-ffffffe0004f4a74: fb_get_color_depth (STB_GLOBAL)
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
int fb_get_color_depth(struct fb_var_screeninfo *var, struct fb_fix_screeninfo *fix);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff815b1440)
Location: drivers/video/fbdev/core/fbmem.c:87
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_palette
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:get_color
  - drivers/video/fbdev/core/bitblit.c:bit_cursor
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
  - drivers/video/fbdev/core/fbcon_cw.c:cw_cursor
  - drivers/video/fbdev/core/fbcon_cw.c:cw_putcs
  - drivers/video/fbdev/core/fbcon_ud.c:ud_cursor
  - drivers/video/fbdev/core/fbcon_ud.c:ud_putcs
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_cursor
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_putcs
```
**Symbols:**

```
ffffffff815b1440-ffffffff815b147a: fb_get_color_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int fb_get_color_depth(struct fb_var_screeninfo *var, struct fb_fix_screeninfo *fix);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff815a05d0)
Location: drivers/video/fbdev/core/fbmem.c:87
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_palette
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:get_color
  - drivers/video/fbdev/core/bitblit.c:bit_cursor
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
  - drivers/video/fbdev/core/fbcon_cw.c:cw_cursor
  - drivers/video/fbdev/core/fbcon_cw.c:cw_putcs
  - drivers/video/fbdev/core/fbcon_ud.c:ud_cursor
  - drivers/video/fbdev/core/fbcon_ud.c:ud_putcs
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_cursor
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_putcs
```
**Symbols:**

```
ffffffff815a05d0-ffffffff815a060a: fb_get_color_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int fb_get_color_depth(struct fb_var_screeninfo *var, struct fb_fix_screeninfo *fix);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff815b19d0)
Location: drivers/video/fbdev/core/fbmem.c:87
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_palette
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:get_color
  - drivers/video/fbdev/core/bitblit.c:bit_cursor
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
  - drivers/video/fbdev/core/fbcon_cw.c:cw_cursor
  - drivers/video/fbdev/core/fbcon_cw.c:cw_putcs
  - drivers/video/fbdev/core/fbcon_ud.c:ud_cursor
  - drivers/video/fbdev/core/fbcon_ud.c:ud_putcs
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_cursor
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_putcs
```
**Symbols:**

```
ffffffff815b19d0-ffffffff815b1a0a: fb_get_color_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int fb_get_color_depth(struct fb_var_screeninfo *var, struct fb_fix_screeninfo *fix);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff815cb440)
Location: drivers/video/fbdev/core/fbmem.c:87
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_palette
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_disp
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo
  - drivers/video/fbdev/core/fbcon.c:get_color
  - drivers/video/fbdev/core/bitblit.c:bit_cursor
  - drivers/video/fbdev/core/bitblit.c:bit_putcs
  - drivers/video/fbdev/core/fbcon_cw.c:cw_cursor
  - drivers/video/fbdev/core/fbcon_cw.c:cw_putcs
  - drivers/video/fbdev/core/fbcon_ud.c:ud_cursor
  - drivers/video/fbdev/core/fbcon_ud.c:ud_putcs
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_cursor
  - drivers/video/fbdev/core/fbcon_ccw.c:ccw_putcs
```
**Symbols:**

```
ffffffff815cb440-ffffffff815cb47a: fb_get_color_depth (STB_GLOBAL)
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
