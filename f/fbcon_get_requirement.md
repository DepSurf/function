# Function: <code>fbcon_get_requirement</code>

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
In drivers/video/console/fbcon.c (ffffffff81465d18)
Location: drivers/video/console/fbcon.c:3215
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
In drivers/video/console/fbcon.c (ffffffff814b3fec)
Location: drivers/video/console/fbcon.c:3213
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
In drivers/video/console/fbcon.c (ffffffff814d601c)
Location: drivers/video/console/fbcon.c:3224
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
In drivers/video/console/fbcon.c (ffffffff814e0f53)
Location: drivers/video/console/fbcon.c:3222
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
In drivers/video/fbdev/core/fbcon.c (ffffffff8152ac09)
Location: drivers/video/fbdev/core/fbcon.c:3238
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
In drivers/video/fbdev/core/fbcon.c (ffffffff8155fd60)
Location: drivers/video/fbdev/core/fbcon.c:3246
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
In drivers/video/fbdev/core/fbcon.c (ffffffff815780ac)
Location: drivers/video/fbdev/core/fbcon.c:3287
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
void fbcon_get_requirement(struct fb_info *info, struct fb_blit_caps *caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815a88f0)
Location: drivers/video/fbdev/core/fbcon.c:3306
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
ffffffff815a88f0-ffffffff815a8a25: fbcon_get_requirement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fbcon_get_requirement(struct fb_info *info, struct fb_blit_caps *caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815c9880)
Location: drivers/video/fbdev/core/fbcon.c:3306
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
ffffffff815c9880-ffffffff815c99b5: fbcon_get_requirement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fbcon_get_requirement(struct fb_info *info, struct fb_blit_caps *caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff81673110)
Location: drivers/video/fbdev/core/fbcon.c:3015
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_check_caps
```
**Symbols:**

```
ffffffff81673110-ffffffff81673243: fbcon_get_requirement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fbcon_get_requirement(struct fb_info *info, struct fb_blit_caps *caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff816934d0)
Location: drivers/video/fbdev/core/fbcon.c:2972
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_check_caps
```
**Symbols:**

```
ffffffff816934d0-ffffffff816935c6: fbcon_get_requirement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fbcon_get_requirement(struct fb_info *info, struct fb_blit_caps *caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff816762b0)
Location: drivers/video/fbdev/core/fbcon.c:2964
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
ffffffff816762b0-ffffffff816763a6: fbcon_get_requirement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void fbcon_get_requirement(struct fb_info *info, struct fb_blit_caps *caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:3009
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
ffffffff81cec90d-ffffffff81cec9a1: fbcon_get_requirement.cold (STB_LOCAL)
ffffffff816eafa0-ffffffff816eb1a1: fbcon_get_requirement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void fbcon_get_requirement(struct fb_info *info, struct fb_blit_caps *caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:3082
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
ffffffff81eb3e1f-ffffffff81eb3eb3: fbcon_get_requirement.cold (STB_LOCAL)
ffffffff81816370-ffffffff81816585: fbcon_get_requirement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void fbcon_get_requirement(struct fb_info *info, struct fb_blit_caps *caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:3080
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
ffffffff8209088a-ffffffff8209091e: fbcon_get_requirement.cold (STB_LOCAL)
ffffffff81945600-ffffffff81945815: fbcon_get_requirement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void fbcon_get_requirement(struct fb_info *info, struct fb_blit_caps *caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:3073
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
ffffffff82110b85-ffffffff82110c19: fbcon_get_requirement.cold (STB_LOCAL)
ffffffff81989c40-ffffffff81989e55: fbcon_get_requirement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void fbcon_get_requirement(struct fb_info *info, struct fb_blit_caps *caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:3073
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
ffffffff821ee9bd-ffffffff821eea51: fbcon_get_requirement.cold (STB_LOCAL)
ffffffff819d3b50-ffffffff819d3d65: fbcon_get_requirement (STB_GLOBAL)
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
void fbcon_get_requirement(struct fb_info *info, struct fb_blit_caps *caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffff800010752dd0)
Location: drivers/video/fbdev/core/fbcon.c:3306
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
ffff800010752dd0-ffff800010752f50: fbcon_get_requirement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fbcon_get_requirement(struct fb_info *info, struct fb_blit_caps *caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (c08d55f8)
Location: drivers/video/fbdev/core/fbcon.c:3306
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
c08d55f8-c08d5784: fbcon_get_requirement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fbcon_get_requirement(struct fb_info *info, struct fb_blit_caps *caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (c0000000008b6f00)
Location: drivers/video/fbdev/core/fbcon.c:3306
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
c0000000008b6f00-c0000000008b70f8: fbcon_get_requirement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fbcon_get_requirement(struct fb_info *info, struct fb_blit_caps *caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffe0004ffda2)
Location: drivers/video/fbdev/core/fbcon.c:3306
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
ffffffe0004ffda2-ffffffe0004ffeda: fbcon_get_requirement (STB_GLOBAL)
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
void fbcon_get_requirement(struct fb_info *info, struct fb_blit_caps *caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815bd8e0)
Location: drivers/video/fbdev/core/fbcon.c:3306
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
ffffffff815bd8e0-ffffffff815bda15: fbcon_get_requirement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fbcon_get_requirement(struct fb_info *info, struct fb_blit_caps *caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815ac6c0)
Location: drivers/video/fbdev/core/fbcon.c:3306
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
ffffffff815ac6c0-ffffffff815ac7f5: fbcon_get_requirement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fbcon_get_requirement(struct fb_info *info, struct fb_blit_caps *caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815bde70)
Location: drivers/video/fbdev/core/fbcon.c:3306
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
ffffffff815bde70-ffffffff815bdfa5: fbcon_get_requirement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fbcon_get_requirement(struct fb_info *info, struct fb_blit_caps *caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815d79c0)
Location: drivers/video/fbdev/core/fbcon.c:3306
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
ffffffff815d79c0-ffffffff815d7af5: fbcon_get_requirement (STB_GLOBAL)
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
