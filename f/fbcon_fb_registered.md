# Function: <code>fbcon_fb_registered</code>

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
In drivers/video/console/fbcon.c (ffffffff81465a75)
Location: drivers/video/console/fbcon.c:3145
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
In drivers/video/console/fbcon.c (ffffffff814b3d33)
Location: drivers/video/console/fbcon.c:3143
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
In drivers/video/console/fbcon.c (ffffffff814d5d63)
Location: drivers/video/console/fbcon.c:3154
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
In drivers/video/console/fbcon.c (ffffffff814e1095)
Location: drivers/video/console/fbcon.c:3152
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
In drivers/video/fbdev/core/fbcon.c (ffffffff8152ad4b)
Location: drivers/video/fbdev/core/fbcon.c:3168
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
In drivers/video/fbdev/core/fbcon.c (ffffffff8155fb86)
Location: drivers/video/fbdev/core/fbcon.c:3176
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
In drivers/video/fbdev/core/fbcon.c (ffffffff815783af)
Location: drivers/video/fbdev/core/fbcon.c:3210
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_event_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int fbcon_fb_registered(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:3229
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
```
**Symbols:**

```
ffffffff815a8cb2-ffffffff815a8d48: fbcon_fb_registered.cold (STB_LOCAL)
ffffffff815a8680-ffffffff815a876a: fbcon_fb_registered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int fbcon_fb_registered(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:3229
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs
```
**Symbols:**

```
ffffffff815c9c38-ffffffff815c9cce: fbcon_fb_registered.cold (STB_LOCAL)
ffffffff815c95c0-ffffffff815c96b9: fbcon_fb_registered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int fbcon_fb_registered(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:2938
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
  - drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs
```
**Symbols:**

```
ffffffff8167358a-ffffffff8167359d: fbcon_fb_registered.cold (STB_LOCAL)
ffffffff81672e60-ffffffff81672f43: fbcon_fb_registered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int fbcon_fb_registered(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:2895
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
  - drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs
```
**Symbols:**

```
ffffffff81bff20e-ffffffff81bff221: fbcon_fb_registered.cold (STB_LOCAL)
ffffffff81693220-ffffffff81693303: fbcon_fb_registered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int fbcon_fb_registered(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:2887
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
  - drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs
```
**Symbols:**

```
ffffffff81bf0c80-ffffffff81bf0d16: fbcon_fb_registered.cold (STB_LOCAL)
ffffffff81675ff0-ffffffff816760e9: fbcon_fb_registered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fbcon_fb_registered(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:2932
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
  - drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs
```
**Symbols:**

```
ffffffff81cec84a-ffffffff81cec90d: fbcon_fb_registered.cold (STB_LOCAL)
ffffffff816eab00-ffffffff816eac5b: fbcon_fb_registered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fbcon_fb_registered(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:3020
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
```
**Symbols:**

```
ffffffff81eb3def-ffffffff81eb3e1f: fbcon_fb_registered.cold (STB_LOCAL)
ffffffff81815fb0-ffffffff8181603d: fbcon_fb_registered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int fbcon_fb_registered(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:3018
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
```
**Symbols:**

```
ffffffff8209085a-ffffffff8209088a: fbcon_fb_registered.cold (STB_LOCAL)
ffffffff81945210-ffffffff8194529d: fbcon_fb_registered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int fbcon_fb_registered(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:3011
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
```
**Symbols:**

```
ffffffff82110b55-ffffffff82110b85: fbcon_fb_registered.cold (STB_LOCAL)
ffffffff81989850-ffffffff819898dd: fbcon_fb_registered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int fbcon_fb_registered(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:3011
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
```
**Symbols:**

```
ffffffff821ee98d-ffffffff821ee9bd: fbcon_fb_registered.cold (STB_LOCAL)
ffffffff819d3760-ffffffff819d37ed: fbcon_fb_registered (STB_GLOBAL)
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
int fbcon_fb_registered(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffff800010752a68)
Location: drivers/video/fbdev/core/fbcon.c:3229
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs
```
**Symbols:**

```
ffff800010752a68-ffff800010752b94: fbcon_fb_registered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fbcon_fb_registered(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (c08d52a4)
Location: drivers/video/fbdev/core/fbcon.c:3229
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs
```
**Symbols:**

```
c08d52a4-c08d53f4: fbcon_fb_registered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fbcon_fb_registered(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (c0000000008b69c0)
Location: drivers/video/fbdev/core/fbcon.c:3229
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs
```
**Symbols:**

```
c0000000008b69c0-c0000000008b6bcc: fbcon_fb_registered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fbcon_fb_registered(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffe0004ffa90)
Location: drivers/video/fbdev/core/fbcon.c:3229
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs
```
**Symbols:**

```
ffffffe0004ffa90-ffffffe0004ffba2: fbcon_fb_registered (STB_GLOBAL)
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
int fbcon_fb_registered(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:3229
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
```
**Symbols:**

```
ffffffff815bdc50-ffffffff815bdcd3: fbcon_fb_registered.cold (STB_LOCAL)
ffffffff815bd670-ffffffff815bd75c: fbcon_fb_registered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int fbcon_fb_registered(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:3229
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
```
**Symbols:**

```
ffffffff815aca30-ffffffff815acab3: fbcon_fb_registered.cold (STB_LOCAL)
ffffffff815ac450-ffffffff815ac53c: fbcon_fb_registered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int fbcon_fb_registered(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:3229
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
```
**Symbols:**

```
ffffffff815be1e0-ffffffff815be263: fbcon_fb_registered.cold (STB_LOCAL)
ffffffff815bdc00-ffffffff815bdcec: fbcon_fb_registered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int fbcon_fb_registered(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:3229
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs
```
**Symbols:**

```
ffffffff815d7d78-ffffffff815d7e0e: fbcon_fb_registered.cold (STB_LOCAL)
ffffffff815d7700-ffffffff815d77f9: fbcon_fb_registered (STB_GLOBAL)
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
