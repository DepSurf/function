# Function: <code>fbcon_mode_deleted</code>

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
In drivers/video/console/fbcon.c (ffffffff81465adf)
Location: drivers/video/console/fbcon.c:2965
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
In drivers/video/console/fbcon.c (ffffffff814b3da3)
Location: drivers/video/console/fbcon.c:2963
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
In drivers/video/console/fbcon.c (ffffffff814d5dd3)
Location: drivers/video/console/fbcon.c:2974
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
In drivers/video/console/fbcon.c (ffffffff814e1107)
Location: drivers/video/console/fbcon.c:2972
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
In drivers/video/fbdev/core/fbcon.c (ffffffff8152adbd)
Location: drivers/video/fbdev/core/fbcon.c:2988
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
In drivers/video/fbdev/core/fbcon.c (ffffffff8155fb24)
Location: drivers/video/fbdev/core/fbcon.c:2996
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
In drivers/video/fbdev/core/fbcon.c (ffffffff81577f9f)
Location: drivers/video/fbdev/core/fbcon.c:3015
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
int fbcon_mode_deleted(struct fb_info *info, struct fb_videomode *mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815a8320)
Location: drivers/video/fbdev/core/fbcon.c:3042
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
ffffffff815a8320-ffffffff815a839a: fbcon_mode_deleted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fbcon_mode_deleted(struct fb_info *info, struct fb_videomode *mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815c9210)
Location: drivers/video/fbdev/core/fbcon.c:3042
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
ffffffff815c9210-ffffffff815c928a: fbcon_mode_deleted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fbcon_mode_deleted(struct fb_info *info, struct fb_videomode *mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff81672ab0)
Location: drivers/video/fbdev/core/fbcon.c:2751
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
ffffffff81672ab0-ffffffff81672b2a: fbcon_mode_deleted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fbcon_mode_deleted(struct fb_info *info, struct fb_videomode *mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff81692e70)
Location: drivers/video/fbdev/core/fbcon.c:2708
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
ffffffff81692e70-ffffffff81692eea: fbcon_mode_deleted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fbcon_mode_deleted(struct fb_info *info, struct fb_videomode *mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff81675c40)
Location: drivers/video/fbdev/core/fbcon.c:2700
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
ffffffff81675c40-ffffffff81675cba: fbcon_mode_deleted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fbcon_mode_deleted(struct fb_info *info, struct fb_videomode *mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff816ea3f0)
Location: drivers/video/fbdev/core/fbcon.c:2745
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
ffffffff816ea3f0-ffffffff816ea4d4: fbcon_mode_deleted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fbcon_mode_deleted(struct fb_info *info, struct fb_videomode *mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff81815820)
Location: drivers/video/fbdev/core/fbcon.c:2788
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
ffffffff81815820-ffffffff81815925: fbcon_mode_deleted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fbcon_mode_deleted(struct fb_info *info, struct fb_videomode *mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff81944a10)
Location: drivers/video/fbdev/core/fbcon.c:2786
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
ffffffff81944a10-ffffffff81944b15: fbcon_mode_deleted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fbcon_mode_deleted(struct fb_info *info, struct fb_videomode *mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff81989050)
Location: drivers/video/fbdev/core/fbcon.c:2779
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
ffffffff81989050-ffffffff81989155: fbcon_mode_deleted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fbcon_mode_deleted(struct fb_info *info, struct fb_videomode *mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff819d2f40)
Location: drivers/video/fbdev/core/fbcon.c:2779
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
ffffffff819d2f40-ffffffff819d3045: fbcon_mode_deleted (STB_GLOBAL)
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
int fbcon_mode_deleted(struct fb_info *info, struct fb_videomode *mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffff800010752578)
Location: drivers/video/fbdev/core/fbcon.c:3042
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
ffff800010752578-ffff800010752650: fbcon_mode_deleted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fbcon_mode_deleted(struct fb_info *info, struct fb_videomode *mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (c08d4db4)
Location: drivers/video/fbdev/core/fbcon.c:3042
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
c08d4db4-c08d4e68: fbcon_mode_deleted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fbcon_mode_deleted(struct fb_info *info, struct fb_videomode *mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (c0000000008b6230)
Location: drivers/video/fbdev/core/fbcon.c:3042
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
c0000000008b6230-c0000000008b6344: fbcon_mode_deleted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fbcon_mode_deleted(struct fb_info *info, struct fb_videomode *mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffe0004ff64e)
Location: drivers/video/fbdev/core/fbcon.c:3042
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
ffffffe0004ff64e-ffffffe0004ff6fe: fbcon_mode_deleted (STB_GLOBAL)
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
int fbcon_mode_deleted(struct fb_info *info, struct fb_videomode *mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815bd310)
Location: drivers/video/fbdev/core/fbcon.c:3042
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
ffffffff815bd310-ffffffff815bd38a: fbcon_mode_deleted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fbcon_mode_deleted(struct fb_info *info, struct fb_videomode *mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815ac0f0)
Location: drivers/video/fbdev/core/fbcon.c:3042
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
ffffffff815ac0f0-ffffffff815ac16a: fbcon_mode_deleted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fbcon_mode_deleted(struct fb_info *info, struct fb_videomode *mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815bd8a0)
Location: drivers/video/fbdev/core/fbcon.c:3042
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
ffffffff815bd8a0-ffffffff815bd91a: fbcon_mode_deleted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fbcon_mode_deleted(struct fb_info *info, struct fb_videomode *mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815d7350)
Location: drivers/video/fbdev/core/fbcon.c:3042
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
ffffffff815d7350-ffffffff815d73ca: fbcon_mode_deleted (STB_GLOBAL)
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
