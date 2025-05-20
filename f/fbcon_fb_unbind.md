# Function: <code>fbcon_fb_unbind</code>

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
In drivers/video/console/fbcon.c (ffffffff81465c38)
Location: drivers/video/console/fbcon.c:3012
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
In drivers/video/console/fbcon.c (ffffffff814b3f0a)
Location: drivers/video/console/fbcon.c:3010
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
In drivers/video/console/fbcon.c (ffffffff814d5f3a)
Location: drivers/video/console/fbcon.c:3021
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
In drivers/video/console/fbcon.c (ffffffff814e0eb7)
Location: drivers/video/console/fbcon.c:3019
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
In drivers/video/fbdev/core/fbcon.c (ffffffff8152ab6d)
Location: drivers/video/fbdev/core/fbcon.c:3035
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
In drivers/video/fbdev/core/fbcon.c (ffffffff8155fe0f)
Location: drivers/video/fbdev/core/fbcon.c:3043
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
In drivers/video/fbdev/core/fbcon.c (ffffffff8157824a)
Location: drivers/video/fbdev/core/fbcon.c:3062
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
void fbcon_fb_unbind(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:3084
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
```
**Symbols:**

```
ffffffff815a8c5f-ffffffff815a8c72: fbcon_fb_unbind.cold (STB_LOCAL)
ffffffff815a83a0-ffffffff815a852c: fbcon_fb_unbind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fbcon_fb_unbind(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815c9290)
Location: drivers/video/fbdev/core/fbcon.c:3084
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
```
**Symbols:**

```
ffffffff815c9290-ffffffff815c941e: fbcon_fb_unbind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fbcon_fb_unbind(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff81672b30)
Location: drivers/video/fbdev/core/fbcon.c:2793
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
```
**Symbols:**

```
ffffffff81672b30-ffffffff81672cbe: fbcon_fb_unbind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fbcon_fb_unbind(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff81692ef0)
Location: drivers/video/fbdev/core/fbcon.c:2750
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
```
**Symbols:**

```
ffffffff81692ef0-ffffffff8169307e: fbcon_fb_unbind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fbcon_fb_unbind(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff81675cc0)
Location: drivers/video/fbdev/core/fbcon.c:2742
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
```
**Symbols:**

```
ffffffff81675cc0-ffffffff81675e4e: fbcon_fb_unbind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fbcon_fb_unbind(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff816ea4e0)
Location: drivers/video/fbdev/core/fbcon.c:2787
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
```
**Symbols:**

```
ffffffff816ea4e0-ffffffff816ea866: fbcon_fb_unbind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fbcon_fb_unbind(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff81815930)
Location: drivers/video/fbdev/core/fbcon.c:2829
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
```
**Symbols:**

```
ffffffff81815930-ffffffff81815c8d: fbcon_fb_unbind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fbcon_fb_unbind(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff81944b30)
Location: drivers/video/fbdev/core/fbcon.c:2827
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:unregister_framebuffer
```
**Symbols:**

```
ffffffff81944b30-ffffffff81944e8d: fbcon_fb_unbind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fbcon_fb_unbind(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff81989170)
Location: drivers/video/fbdev/core/fbcon.c:2820
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:unregister_framebuffer
```
**Symbols:**

```
ffffffff81989170-ffffffff819894cd: fbcon_fb_unbind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fbcon_fb_unbind(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff819d3060)
Location: drivers/video/fbdev/core/fbcon.c:2820
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:unregister_framebuffer
```
**Symbols:**

```
ffffffff819d3060-ffffffff819d33bd: fbcon_fb_unbind (STB_GLOBAL)
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
void fbcon_fb_unbind(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffff800010752650)
Location: drivers/video/fbdev/core/fbcon.c:3084
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
```
**Symbols:**

```
ffff800010752650-ffff80001075282c: fbcon_fb_unbind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fbcon_fb_unbind(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (c08d4e68)
Location: drivers/video/fbdev/core/fbcon.c:3084
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
```
**Symbols:**

```
c08d4e68-c08d504c: fbcon_fb_unbind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fbcon_fb_unbind(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (c0000000008b6350)
Location: drivers/video/fbdev/core/fbcon.c:3084
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
```
**Symbols:**

```
c0000000008b6350-c0000000008b6644: fbcon_fb_unbind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fbcon_fb_unbind(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffe0004ff6fe)
Location: drivers/video/fbdev/core/fbcon.c:3084
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
```
**Symbols:**

```
ffffffe0004ff6fe-ffffffe0004ff880: fbcon_fb_unbind (STB_GLOBAL)
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
void fbcon_fb_unbind(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815bd390)
Location: drivers/video/fbdev/core/fbcon.c:3084
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
```
**Symbols:**

```
ffffffff815bd390-ffffffff815bd51e: fbcon_fb_unbind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fbcon_fb_unbind(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815ac170)
Location: drivers/video/fbdev/core/fbcon.c:3084
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
```
**Symbols:**

```
ffffffff815ac170-ffffffff815ac2fe: fbcon_fb_unbind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fbcon_fb_unbind(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815bd920)
Location: drivers/video/fbdev/core/fbcon.c:3084
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
```
**Symbols:**

```
ffffffff815bd920-ffffffff815bdaae: fbcon_fb_unbind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fbcon_fb_unbind(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815d73d0)
Location: drivers/video/fbdev/core/fbcon.c:3084
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
```
**Symbols:**

```
ffffffff815d73d0-ffffffff815d755e: fbcon_fb_unbind (STB_GLOBAL)
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
