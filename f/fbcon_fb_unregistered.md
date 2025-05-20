# Function: <code>fbcon_fb_unregistered</code>

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
In drivers/video/console/fbcon.c (ffffffff81465a35)
Location: drivers/video/console/fbcon.c:3062
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
In drivers/video/console/fbcon.c (ffffffff814b3cef)
Location: drivers/video/console/fbcon.c:3060
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
In drivers/video/console/fbcon.c (ffffffff814d5d1f)
Location: drivers/video/console/fbcon.c:3071
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
In drivers/video/console/fbcon.c (ffffffff814e0ff7)
Location: drivers/video/console/fbcon.c:3069
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
In drivers/video/fbdev/core/fbcon.c (ffffffff8152acad)
Location: drivers/video/fbdev/core/fbcon.c:3085
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
In drivers/video/fbdev/core/fbcon.c (ffffffff8155fc1b)
Location: drivers/video/fbdev/core/fbcon.c:3093
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
In drivers/video/fbdev/core/fbcon.c (ffffffff81578162)
Location: drivers/video/fbdev/core/fbcon.c:3114
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
void fbcon_fb_unregistered(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:3135
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
```
**Symbols:**

```
ffffffff815a8c72-ffffffff815a8c85: fbcon_fb_unregistered.cold (STB_LOCAL)
ffffffff815a8530-ffffffff815a861d: fbcon_fb_unregistered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fbcon_fb_unregistered(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815c9420)
Location: drivers/video/fbdev/core/fbcon.c:3135
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
```
**Symbols:**

```
ffffffff815c9420-ffffffff815c9519: fbcon_fb_unregistered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fbcon_fb_unregistered(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff81672cc0)
Location: drivers/video/fbdev/core/fbcon.c:2844
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
```
**Symbols:**

```
ffffffff81672cc0-ffffffff81672dbc: fbcon_fb_unregistered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fbcon_fb_unregistered(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff81693080)
Location: drivers/video/fbdev/core/fbcon.c:2801
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
```
**Symbols:**

```
ffffffff81693080-ffffffff8169317c: fbcon_fb_unregistered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fbcon_fb_unregistered(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff81675e50)
Location: drivers/video/fbdev/core/fbcon.c:2793
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
```
**Symbols:**

```
ffffffff81675e50-ffffffff81675f4c: fbcon_fb_unregistered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void fbcon_fb_unregistered(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:2838
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
```
**Symbols:**

```
ffffffff81cec7f3-ffffffff81cec808: fbcon_fb_unregistered.cold (STB_LOCAL)
ffffffff816ea870-ffffffff816eaa40: fbcon_fb_unregistered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void fbcon_fb_unregistered(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:2878
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
```
**Symbols:**

```
ffffffff81eb3d98-ffffffff81eb3dad: fbcon_fb_unregistered.cold (STB_LOCAL)
ffffffff81815c90-ffffffff81815ed0: fbcon_fb_unregistered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void fbcon_fb_unregistered(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:2876
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:unregister_framebuffer
```
**Symbols:**

```
ffffffff82090830-ffffffff82090845: fbcon_fb_unregistered.cold (STB_LOCAL)
ffffffff81944ea0-ffffffff819450e0: fbcon_fb_unregistered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void fbcon_fb_unregistered(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:2869
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:unregister_framebuffer
```
**Symbols:**

```
ffffffff82110b2b-ffffffff82110b40: fbcon_fb_unregistered.cold (STB_LOCAL)
ffffffff819894e0-ffffffff81989720: fbcon_fb_unregistered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void fbcon_fb_unregistered(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:2869
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:unregister_framebuffer
```
**Symbols:**

```
ffffffff821ee95d-ffffffff821ee978: fbcon_fb_unregistered.cold (STB_LOCAL)
ffffffff819d33d0-ffffffff819d362f: fbcon_fb_unregistered (STB_GLOBAL)
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
void fbcon_fb_unregistered(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffff800010752830)
Location: drivers/video/fbdev/core/fbcon.c:3135
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
```
**Symbols:**

```
ffff800010752830-ffff800010752968: fbcon_fb_unregistered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fbcon_fb_unregistered(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (c08d504c)
Location: drivers/video/fbdev/core/fbcon.c:3135
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
```
**Symbols:**

```
c08d504c-c08d51b4: fbcon_fb_unregistered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fbcon_fb_unregistered(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (c0000000008b6650)
Location: drivers/video/fbdev/core/fbcon.c:3135
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
```
**Symbols:**

```
c0000000008b6650-c0000000008b683c: fbcon_fb_unregistered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fbcon_fb_unregistered(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffe0004ff880)
Location: drivers/video/fbdev/core/fbcon.c:3135
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
```
**Symbols:**

```
ffffffe0004ff880-ffffffe0004ff9a4: fbcon_fb_unregistered (STB_GLOBAL)
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
void fbcon_fb_unregistered(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815bd520)
Location: drivers/video/fbdev/core/fbcon.c:3135
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
```
**Symbols:**

```
ffffffff815bd520-ffffffff815bd60f: fbcon_fb_unregistered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fbcon_fb_unregistered(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815ac300)
Location: drivers/video/fbdev/core/fbcon.c:3135
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
```
**Symbols:**

```
ffffffff815ac300-ffffffff815ac3ef: fbcon_fb_unregistered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fbcon_fb_unregistered(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815bdab0)
Location: drivers/video/fbdev/core/fbcon.c:3135
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
```
**Symbols:**

```
ffffffff815bdab0-ffffffff815bdb9f: fbcon_fb_unregistered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fbcon_fb_unregistered(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815d7560)
Location: drivers/video/fbdev/core/fbcon.c:3135
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
```
**Symbols:**

```
ffffffff815d7560-ffffffff815d7659: fbcon_fb_unregistered (STB_GLOBAL)
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
