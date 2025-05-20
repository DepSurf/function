# Function: <code>fbcon_modechange_possible</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fbcon_modechange_possible(struct fb_info *info, struct fb_var_screeninfo *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff81811060)
Location: drivers/video/fbdev/core/fbcon.c:2761
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
```
**Symbols:**

```
ffffffff81811060-ffffffff818111f4: fbcon_modechange_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fbcon_modechange_possible(struct fb_info *info, struct fb_var_screeninfo *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff8193ff50)
Location: drivers/video/fbdev/core/fbcon.c:2759
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
```
**Symbols:**

```
ffffffff8193ff50-ffffffff819400e4: fbcon_modechange_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fbcon_modechange_possible(struct fb_info *info, struct fb_var_screeninfo *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff81984460)
Location: drivers/video/fbdev/core/fbcon.c:2752
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
```
**Symbols:**

```
ffffffff81984460-ffffffff819845f4: fbcon_modechange_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fbcon_modechange_possible(struct fb_info *info, struct fb_var_screeninfo *var);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff819ce3a0)
Location: drivers/video/fbdev/core/fbcon.c:2752
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fb_chrdev.c:do_fb_ioctl
```
**Symbols:**

```
ffffffff819ce3a0-ffffffff819ce534: fbcon_modechange_possible (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
