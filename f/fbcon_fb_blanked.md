# Function: <code>fbcon_fb_blanked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/console/fbcon.c (ffffffff81465dd4)
Location: drivers/video/console/fbcon.c:3172
Inline: True
Inline callers:
  - drivers/video/console/fbcon.c:fbcon_event_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/console/fbcon.c (ffffffff814b40ab)
Location: drivers/video/console/fbcon.c:3170
Inline: True
Inline callers:
  - drivers/video/console/fbcon.c:fbcon_event_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/console/fbcon.c (ffffffff814d60db)
Location: drivers/video/console/fbcon.c:3181
Inline: True
Inline callers:
  - drivers/video/console/fbcon.c:fbcon_event_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/console/fbcon.c (ffffffff814e120e)
Location: drivers/video/console/fbcon.c:3179
Inline: True
Inline callers:
  - drivers/video/console/fbcon.c:fbcon_event_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff8152aec4)
Location: drivers/video/fbdev/core/fbcon.c:3195
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_event_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff8155fcce)
Location: drivers/video/fbdev/core/fbcon.c:3203
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_event_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815782e8)
Location: drivers/video/fbdev/core/fbcon.c:3244
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_event_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void fbcon_fb_blanked(struct fb_info *info, int blank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815a8770)
Location: drivers/video/fbdev/core/fbcon.c:3263
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
```
**Symbols:**

```
ffffffff815a8770-ffffffff815a87ee: fbcon_fb_blanked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fbcon_fb_blanked(struct fb_info *info, int blank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815c9700)
Location: drivers/video/fbdev/core/fbcon.c:3263
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
```
**Symbols:**

```
ffffffff815c9700-ffffffff815c977e: fbcon_fb_blanked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fbcon_fb_blanked(struct fb_info *info, int blank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff81672f90)
Location: drivers/video/fbdev/core/fbcon.c:2972
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
```
**Symbols:**

```
ffffffff81672f90-ffffffff8167300e: fbcon_fb_blanked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fbcon_fb_blanked(struct fb_info *info, int blank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff81693350)
Location: drivers/video/fbdev/core/fbcon.c:2929
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
```
**Symbols:**

```
ffffffff81693350-ffffffff816933ce: fbcon_fb_blanked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fbcon_fb_blanked(struct fb_info *info, int blank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff81676130)
Location: drivers/video/fbdev/core/fbcon.c:2921
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
```
**Symbols:**

```
ffffffff81676130-ffffffff816761ae: fbcon_fb_blanked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fbcon_fb_blanked(struct fb_info *info, int blank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff816eace0)
Location: drivers/video/fbdev/core/fbcon.c:2966
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
```
**Symbols:**

```
ffffffff816eace0-ffffffff816eadbb: fbcon_fb_blanked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fbcon_fb_blanked(struct fb_info *info, int blank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff81816040)
Location: drivers/video/fbdev/core/fbcon.c:3039
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
```
**Symbols:**

```
ffffffff81816040-ffffffff8181613b: fbcon_fb_blanked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fbcon_fb_blanked(struct fb_info *info, int blank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff819452b0)
Location: drivers/video/fbdev/core/fbcon.c:3037
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
```
**Symbols:**

```
ffffffff819452b0-ffffffff819453ab: fbcon_fb_blanked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fbcon_fb_blanked(struct fb_info *info, int blank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff819898f0)
Location: drivers/video/fbdev/core/fbcon.c:3030
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
```
**Symbols:**

```
ffffffff819898f0-ffffffff819899eb: fbcon_fb_blanked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fbcon_fb_blanked(struct fb_info *info, int blank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff819d3800)
Location: drivers/video/fbdev/core/fbcon.c:3030
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fb_chrdev.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
```
**Symbols:**

```
ffffffff819d3800-ffffffff819d38fb: fbcon_fb_blanked (STB_GLOBAL)
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
void fbcon_fb_blanked(struct fb_info *info, int blank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffff800010752be8)
Location: drivers/video/fbdev/core/fbcon.c:3263
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
```
**Symbols:**

```
ffff800010752be8-ffff800010752c9c: fbcon_fb_blanked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fbcon_fb_blanked(struct fb_info *info, int blank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (c08d5438)
Location: drivers/video/fbdev/core/fbcon.c:3263
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
```
**Symbols:**

```
c08d5438-c08d54dc: fbcon_fb_blanked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fbcon_fb_blanked(struct fb_info *info, int blank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (c0000000008b6c50)
Location: drivers/video/fbdev/core/fbcon.c:3263
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
```
**Symbols:**

```
c0000000008b6c50-c0000000008b6d48: fbcon_fb_blanked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fbcon_fb_blanked(struct fb_info *info, int blank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffe0004ffbf6)
Location: drivers/video/fbdev/core/fbcon.c:3263
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
```
**Symbols:**

```
ffffffe0004ffbf6-ffffffe0004ffca4: fbcon_fb_blanked (STB_GLOBAL)
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
void fbcon_fb_blanked(struct fb_info *info, int blank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815bd760)
Location: drivers/video/fbdev/core/fbcon.c:3263
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
```
**Symbols:**

```
ffffffff815bd760-ffffffff815bd7de: fbcon_fb_blanked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fbcon_fb_blanked(struct fb_info *info, int blank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815ac540)
Location: drivers/video/fbdev/core/fbcon.c:3263
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
```
**Symbols:**

```
ffffffff815ac540-ffffffff815ac5be: fbcon_fb_blanked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fbcon_fb_blanked(struct fb_info *info, int blank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815bdcf0)
Location: drivers/video/fbdev/core/fbcon.c:3263
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
```
**Symbols:**

```
ffffffff815bdcf0-ffffffff815bdd6e: fbcon_fb_blanked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fbcon_fb_blanked(struct fb_info *info, int blank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815d7840)
Location: drivers/video/fbdev/core/fbcon.c:3263
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbsysfs.c:store_blank
```
**Symbols:**

```
ffffffff815d7840-ffffffff815d78be: fbcon_fb_blanked (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
