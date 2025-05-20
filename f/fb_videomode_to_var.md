# Function: <code>fb_videomode_to_var</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void fb_videomode_to_var(struct fb_var_screeninfo *var, const struct fb_videomode *mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/modedb.c (ffffffff81471fb0)
Location: drivers/video/fbdev/core/modedb.c:926
Inline: False
Direct callers:
  - drivers/video/console/fbcon.c:display_to_var
  - drivers/video/console/fbcon.c:fbcon_new_modelist
  - drivers/video/console/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbsysfs.c:store_mode
```
**Symbols:**

```
ffffffff81471fb0-ffffffff8147201d: fb_videomode_to_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void fb_videomode_to_var(struct fb_var_screeninfo *var, const struct fb_videomode *mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/modedb.c (ffffffff814c0470)
Location: drivers/video/fbdev/core/modedb.c:926
Inline: False
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_new_modelist
  - drivers/video/console/fbcon.c:fbcon_resize
  - drivers/video/console/fbcon.c:display_to_var
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbsysfs.c:store_mode
```
**Symbols:**

```
ffffffff814c0470-ffffffff814c04dd: fb_videomode_to_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void fb_videomode_to_var(struct fb_var_screeninfo *var, const struct fb_videomode *mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/modedb.c (ffffffff814e2460)
Location: drivers/video/fbdev/core/modedb.c:926
Inline: False
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_new_modelist
  - drivers/video/console/fbcon.c:fbcon_resize
  - drivers/video/console/fbcon.c:display_to_var
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbsysfs.c:store_mode
```
**Symbols:**

```
ffffffff814e2460-ffffffff814e24cd: fb_videomode_to_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void fb_videomode_to_var(struct fb_var_screeninfo *var, const struct fb_videomode *mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/modedb.c (ffffffff814ee190)
Location: drivers/video/fbdev/core/modedb.c:926
Inline: False
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_new_modelist
  - drivers/video/console/fbcon.c:fbcon_resize
  - drivers/video/console/fbcon.c:display_to_var
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbsysfs.c:store_mode
```
**Symbols:**

```
ffffffff814ee190-ffffffff814ee1f7: fb_videomode_to_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void fb_videomode_to_var(struct fb_var_screeninfo *var, const struct fb_videomode *mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/modedb.c (ffffffff81522d10)
Location: drivers/video/fbdev/core/modedb.c:926
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbsysfs.c:store_mode
  - drivers/video/fbdev/core/fbcon.c:fbcon_new_modelist
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:display_to_var
```
**Symbols:**

```
ffffffff81522d10-ffffffff81522d77: fb_videomode_to_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void fb_videomode_to_var(struct fb_var_screeninfo *var, const struct fb_videomode *mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/modedb.c (ffffffff815589a0)
Location: drivers/video/fbdev/core/modedb.c:945
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbsysfs.c:store_mode
  - drivers/video/fbdev/core/fbcon.c:fbcon_new_modelist
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:display_to_var
```
**Symbols:**

```
ffffffff815589a0-ffffffff81558a07: fb_videomode_to_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void fb_videomode_to_var(struct fb_var_screeninfo *var, const struct fb_videomode *mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/modedb.c (ffffffff81570330)
Location: drivers/video/fbdev/core/modedb.c:947
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbsysfs.c:store_mode
  - drivers/video/fbdev/core/fbcon.c:fbcon_new_modelist
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:display_to_var
```
**Symbols:**

```
ffffffff81570330-ffffffff81570397: fb_videomode_to_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void fb_videomode_to_var(struct fb_var_screeninfo *var, const struct fb_videomode *mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/modedb.c (ffffffff815a07c0)
Location: drivers/video/fbdev/core/modedb.c:950
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbsysfs.c:store_mode
  - drivers/video/fbdev/core/fbcon.c:fbcon_new_modelist
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:display_to_var
```
**Symbols:**

```
ffffffff815a07c0-ffffffff815a0827: fb_videomode_to_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fb_videomode_to_var(struct fb_var_screeninfo *var, const struct fb_videomode *mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/modedb.c (ffffffff815c1640)
Location: drivers/video/fbdev/core/modedb.c:893
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbsysfs.c:store_mode
  - drivers/video/fbdev/core/fbcon.c:fbcon_new_modelist
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:display_to_var
```
**Symbols:**

```
ffffffff815c1640-ffffffff815c16a7: fb_videomode_to_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fb_videomode_to_var(struct fb_var_screeninfo *var, const struct fb_videomode *mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/modedb.c (ffffffff8166b9c0)
Location: drivers/video/fbdev/core/modedb.c:893
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbsysfs.c:store_mode
  - drivers/video/fbdev/core/fbcon.c:fbcon_new_modelist
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:display_to_var
```
**Symbols:**

```
ffffffff8166b9c0-ffffffff8166ba27: fb_videomode_to_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fb_videomode_to_var(struct fb_var_screeninfo *var, const struct fb_videomode *mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/modedb.c (ffffffff8168c310)
Location: drivers/video/fbdev/core/modedb.c:893
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbsysfs.c:store_mode
  - drivers/video/fbdev/core/fbcon.c:fbcon_new_modelist
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:display_to_var
```
**Symbols:**

```
ffffffff8168c310-ffffffff8168c377: fb_videomode_to_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fb_videomode_to_var(struct fb_var_screeninfo *var, const struct fb_videomode *mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/modedb.c (ffffffff8166efe0)
Location: drivers/video/fbdev/core/modedb.c:893
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbsysfs.c:store_mode
  - drivers/video/fbdev/core/fbcon.c:fbcon_new_modelist
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:display_to_var
```
**Symbols:**

```
ffffffff8166efe0-ffffffff8166f047: fb_videomode_to_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fb_videomode_to_var(struct fb_var_screeninfo *var, const struct fb_videomode *mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/modedb.c (ffffffff816e3200)
Location: drivers/video/fbdev/core/modedb.c:893
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbsysfs.c:store_mode
  - drivers/video/fbdev/core/fbcon.c:fbcon_new_modelist
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:display_to_var
```
**Symbols:**

```
ffffffff816e3200-ffffffff816e3267: fb_videomode_to_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fb_videomode_to_var(struct fb_var_screeninfo *var, const struct fb_videomode *mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/modedb.c (ffffffff8180d710)
Location: drivers/video/fbdev/core/modedb.c:893
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbsysfs.c:store_mode
  - drivers/video/fbdev/core/fbcon.c:fbcon_new_modelist
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:display_to_var
```
**Symbols:**

```
ffffffff8180d710-ffffffff8180d783: fb_videomode_to_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fb_videomode_to_var(struct fb_var_screeninfo *var, const struct fb_videomode *mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/modedb.c (ffffffff8193c2e0)
Location: drivers/video/fbdev/core/modedb.c:893
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbsysfs.c:store_mode
  - drivers/video/fbdev/core/fbcon.c:fbcon_new_modelist
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:display_to_var
```
**Symbols:**

```
ffffffff8193c2e0-ffffffff8193c353: fb_videomode_to_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fb_videomode_to_var(struct fb_var_screeninfo *var, const struct fb_videomode *mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/modedb.c (ffffffff819802c0)
Location: drivers/video/fbdev/core/modedb.c:902
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbsysfs.c:store_mode
  - drivers/video/fbdev/core/fbcon.c:fbcon_new_modelist
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:display_to_var
```
**Symbols:**

```
ffffffff819802c0-ffffffff81980333: fb_videomode_to_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fb_videomode_to_var(struct fb_var_screeninfo *var, const struct fb_videomode *mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/modedb.c (ffffffff819c5600)
Location: drivers/video/fbdev/core/modedb.c:902
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbsysfs.c:store_mode
  - drivers/video/fbdev/core/fbcon.c:fbcon_new_modelist
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:display_to_var
```
**Symbols:**

```
ffffffff819c5600-ffffffff819c5673: fb_videomode_to_var (STB_GLOBAL)
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
void fb_videomode_to_var(struct fb_var_screeninfo *var, const struct fb_videomode *mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/modedb.c (ffff80001074a5c8)
Location: drivers/video/fbdev/core/modedb.c:893
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbsysfs.c:store_mode
  - drivers/video/fbdev/core/fbcon.c:fbcon_new_modelist
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:display_to_var
```
**Symbols:**

```
ffff80001074a5c8-ffff80001074a65c: fb_videomode_to_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fb_videomode_to_var(struct fb_var_screeninfo *var, const struct fb_videomode *mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/modedb.c (c08ccf38)
Location: drivers/video/fbdev/core/modedb.c:893
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbsysfs.c:store_mode
  - drivers/video/fbdev/core/fbcon.c:fbcon_new_modelist
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:display_to_var
```
**Symbols:**

```
c08ccf38-c08ccfc4: fb_videomode_to_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fb_videomode_to_var(struct fb_var_screeninfo *var, const struct fb_videomode *mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/modedb.c (c0000000008abc90)
Location: drivers/video/fbdev/core/modedb.c:893
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbsysfs.c:store_mode
  - drivers/video/fbdev/core/fbcon.c:fbcon_new_modelist
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:display_to_var
```
**Symbols:**

```
c0000000008abc90-c0000000008abd0c: fb_videomode_to_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fb_videomode_to_var(struct fb_var_screeninfo *var, const struct fb_videomode *mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/modedb.c (ffffffe0004f87e6)
Location: drivers/video/fbdev/core/modedb.c:893
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbsysfs.c:store_mode
  - drivers/video/fbdev/core/fbcon.c:fbcon_new_modelist
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:display_to_var
```
**Symbols:**

```
ffffffe0004f87e6-ffffffe0004f8866: fb_videomode_to_var (STB_GLOBAL)
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
void fb_videomode_to_var(struct fb_var_screeninfo *var, const struct fb_videomode *mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/modedb.c (ffffffff815b5790)
Location: drivers/video/fbdev/core/modedb.c:893
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbsysfs.c:store_mode
  - drivers/video/fbdev/core/fbcon.c:fbcon_new_modelist
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:display_to_var
```
**Symbols:**

```
ffffffff815b5790-ffffffff815b57f7: fb_videomode_to_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fb_videomode_to_var(struct fb_var_screeninfo *var, const struct fb_videomode *mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/modedb.c (ffffffff815a4570)
Location: drivers/video/fbdev/core/modedb.c:893
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbsysfs.c:store_mode
  - drivers/video/fbdev/core/fbcon.c:fbcon_new_modelist
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:display_to_var
```
**Symbols:**

```
ffffffff815a4570-ffffffff815a45d7: fb_videomode_to_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fb_videomode_to_var(struct fb_var_screeninfo *var, const struct fb_videomode *mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/modedb.c (ffffffff815b5d20)
Location: drivers/video/fbdev/core/modedb.c:893
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbsysfs.c:store_mode
  - drivers/video/fbdev/core/fbcon.c:fbcon_new_modelist
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:display_to_var
```
**Symbols:**

```
ffffffff815b5d20-ffffffff815b5d87: fb_videomode_to_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fb_videomode_to_var(struct fb_var_screeninfo *var, const struct fb_videomode *mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/modedb.c (ffffffff815cf790)
Location: drivers/video/fbdev/core/modedb.c:893
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_new_modelist
  - drivers/video/fbdev/core/fbsysfs.c:store_mode
  - drivers/video/fbdev/core/fbcon.c:fbcon_new_modelist
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:display_to_var
```
**Symbols:**

```
ffffffff815cf790-ffffffff815cf7f7: fb_videomode_to_var (STB_GLOBAL)
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
