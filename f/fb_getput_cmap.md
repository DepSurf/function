# Function: <code>fb_getput_cmap</code>

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
In drivers/video/fbdev/core/fbmem.c (ffffffff8146d0f4)
Location: drivers/video/fbdev/core/fbmem.c:1263
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
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
In drivers/video/fbdev/core/fbmem.c (ffffffff814bb414)
Location: drivers/video/fbdev/core/fbmem.c:1263
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
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
In drivers/video/fbdev/core/fbmem.c (ffffffff814dd414)
Location: drivers/video/fbdev/core/fbmem.c:1263
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
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
In drivers/video/fbdev/core/fbmem.c (ffffffff814e9bfc)
Location: drivers/video/fbdev/core/fbmem.c:1263
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
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
In drivers/video/fbdev/core/fbmem.c (ffffffff8151e762)
Location: drivers/video/fbdev/core/fbmem.c:1265
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
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
In drivers/video/fbdev/core/fbmem.c (ffffffff815542fe)
Location: drivers/video/fbdev/core/fbmem.c:1253
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
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
In drivers/video/fbdev/core/fbmem.c (ffffffff8156bd59)
Location: drivers/video/fbdev/core/fbmem.c:1284
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff8159c031)
Location: drivers/video/fbdev/core/fbmem.c:1220
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff815bd631)
Location: drivers/video/fbdev/core/fbmem.c:1210
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fb_getput_cmap(struct fb_info *info, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff81666820)
Location: drivers/video/fbdev/core/fbmem.c:1211
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
**Symbols:**

```
ffffffff81666820-ffffffff81666968: fb_getput_cmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fb_getput_cmap(struct fb_info *info, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff81686eb0)
Location: drivers/video/fbdev/core/fbmem.c:1215
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
**Symbols:**

```
ffffffff81686eb0-ffffffff81686fad: fb_getput_cmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fb_getput_cmap(struct fb_info *info, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff81669c60)
Location: drivers/video/fbdev/core/fbmem.c:1213
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
**Symbols:**

```
ffffffff81669c60-ffffffff81669d5d: fb_getput_cmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fb_getput_cmap(struct fb_info *info, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff816dd120)
Location: drivers/video/fbdev/core/fbmem.c:1219
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
**Symbols:**

```
ffffffff816dd120-ffffffff816dd21d: fb_getput_cmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fb_getput_cmap(struct fb_info *info, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff81806fd0)
Location: drivers/video/fbdev/core/fbmem.c:1231
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
**Symbols:**

```
ffffffff81806fd0-ffffffff81807137: fb_getput_cmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fb_getput_cmap(struct fb_info *info, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff81935b40)
Location: drivers/video/fbdev/core/fbmem.c:1233
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
**Symbols:**

```
ffffffff81935b40-ffffffff81935ca7: fb_getput_cmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fb_getput_cmap(struct fb_info *info, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff81979e30)
Location: drivers/video/fbdev/core/fbmem.c:1129
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
**Symbols:**

```
ffffffff81979e30-ffffffff81979f97: fb_getput_cmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fb_getput_cmap(struct fb_info *info, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fb_chrdev.c (ffffffff819ca2d0)
Location: drivers/video/fbdev/core/fb_chrdev.c:199
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fb_chrdev.c:fb_compat_ioctl
```
**Symbols:**

```
ffffffff819ca2d0-ffffffff819ca437: fb_getput_cmap (STB_LOCAL)
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
int fb_getput_cmap(struct fb_info *info, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffff800010745998)
Location: drivers/video/fbdev/core/fbmem.c:1210
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
**Symbols:**

```
ffff800010745998-ffff800010746394: fb_getput_cmap (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fb_getput_cmap(struct fb_info *info, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (c0000000008a6570)
Location: drivers/video/fbdev/core/fbmem.c:1210
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
**Symbols:**

```
c0000000008a6570-c0000000008a6b00: fb_getput_cmap (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff815b1781)
Location: drivers/video/fbdev/core/fbmem.c:1210
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff815a0911)
Location: drivers/video/fbdev/core/fbmem.c:1210
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff815b1d11)
Location: drivers/video/fbdev/core/fbmem.c:1210
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff815cb781)
Location: drivers/video/fbdev/core/fbmem.c:1210
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
