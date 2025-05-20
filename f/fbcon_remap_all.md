# Function: <code>fbcon_remap_all</code>

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
In drivers/video/console/fbcon.c (ffffffff81465bcb)
Location: drivers/video/console/fbcon.c:3100
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
In drivers/video/console/fbcon.c (ffffffff814b3e9d)
Location: drivers/video/console/fbcon.c:3098
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
In drivers/video/console/fbcon.c (ffffffff814d5ecd)
Location: drivers/video/console/fbcon.c:3109
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
In drivers/video/console/fbcon.c (ffffffff814e0e53)
Location: drivers/video/console/fbcon.c:3107
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
In drivers/video/fbdev/core/fbcon.c (ffffffff8152ab09)
Location: drivers/video/fbdev/core/fbcon.c:3123
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
In drivers/video/fbdev/core/fbcon.c (ffffffff8155fa56)
Location: drivers/video/fbdev/core/fbcon.c:3131
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
In drivers/video/fbdev/core/fbcon.c (ffffffff81578050)
Location: drivers/video/fbdev/core/fbcon.c:3155
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
void fbcon_remap_all(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:3173
Inline: False
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
```
**Symbols:**

```
ffffffff815a8c85-ffffffff815a8cb2: fbcon_remap_all.cold (STB_LOCAL)
ffffffff815a8620-ffffffff815a8678: fbcon_remap_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void fbcon_remap_all(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:3173
Inline: False
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
```
**Symbols:**

```
ffffffff815c9c0b-ffffffff815c9c38: fbcon_remap_all.cold (STB_LOCAL)
ffffffff815c9520-ffffffff815c95b7: fbcon_remap_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void fbcon_remap_all(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:2882
Inline: False
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
```
**Symbols:**

```
ffffffff8167355d-ffffffff8167358a: fbcon_remap_all.cold (STB_LOCAL)
ffffffff81672dc0-ffffffff81672e57: fbcon_remap_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void fbcon_remap_all(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:2839
Inline: False
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
```
**Symbols:**

```
ffffffff81bff1e1-ffffffff81bff20e: fbcon_remap_all.cold (STB_LOCAL)
ffffffff81693180-ffffffff81693217: fbcon_remap_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void fbcon_remap_all(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:2831
Inline: False
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
```
**Symbols:**

```
ffffffff81bf0c53-ffffffff81bf0c80: fbcon_remap_all.cold (STB_LOCAL)
ffffffff81675f50-ffffffff81675fe7: fbcon_remap_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void fbcon_remap_all(struct fb_info *info);
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
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
```
**Symbols:**

```
ffffffff81cec808-ffffffff81cec84a: fbcon_remap_all.cold (STB_LOCAL)
ffffffff816eaa40-ffffffff816eaafe: fbcon_remap_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void fbcon_remap_all(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:2922
Inline: False
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
```
**Symbols:**

```
ffffffff81eb3dad-ffffffff81eb3def: fbcon_remap_all.cold (STB_LOCAL)
ffffffff81815ed0-ffffffff81815faa: fbcon_remap_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void fbcon_remap_all(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:2920
Inline: False
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
```
**Symbols:**

```
ffffffff82090845-ffffffff8209085a: fbcon_remap_all.cold (STB_LOCAL)
ffffffff819450f0-ffffffff819451f2: fbcon_remap_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void fbcon_remap_all(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:2913
Inline: False
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
```
**Symbols:**

```
ffffffff82110b40-ffffffff82110b55: fbcon_remap_all.cold (STB_LOCAL)
ffffffff81989730-ffffffff81989832: fbcon_remap_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void fbcon_remap_all(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:2913
Inline: False
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
```
**Symbols:**

```
ffffffff821ee978-ffffffff821ee98d: fbcon_remap_all.cold (STB_LOCAL)
ffffffff819d3640-ffffffff819d3742: fbcon_remap_all (STB_GLOBAL)
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
void fbcon_remap_all(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffff800010752968)
Location: drivers/video/fbdev/core/fbcon.c:3173
Inline: False
```
**Symbols:**

```
ffff800010752968-ffff800010752a64: fbcon_remap_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fbcon_remap_all(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (c08d51b4)
Location: drivers/video/fbdev/core/fbcon.c:3173
Inline: False
```
**Symbols:**

```
c08d51b4-c08d52a4: fbcon_remap_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fbcon_remap_all(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (c0000000008b6840)
Location: drivers/video/fbdev/core/fbcon.c:3173
Inline: False
```
**Symbols:**

```
c0000000008b6840-c0000000008b69c0: fbcon_remap_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fbcon_remap_all(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffe0004ff9a4)
Location: drivers/video/fbdev/core/fbcon.c:3173
Inline: False
```
**Symbols:**

```
ffffffe0004ff9a4-ffffffe0004ffa90: fbcon_remap_all (STB_GLOBAL)
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
void fbcon_remap_all(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:3173
Inline: False
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
```
**Symbols:**

```
ffffffff815bdc23-ffffffff815bdc50: fbcon_remap_all.cold (STB_LOCAL)
ffffffff815bd610-ffffffff815bd668: fbcon_remap_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void fbcon_remap_all(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:3173
Inline: False
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
```
**Symbols:**

```
ffffffff815aca03-ffffffff815aca30: fbcon_remap_all.cold (STB_LOCAL)
ffffffff815ac3f0-ffffffff815ac448: fbcon_remap_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void fbcon_remap_all(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:3173
Inline: False
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
```
**Symbols:**

```
ffffffff815be1b3-ffffffff815be1e0: fbcon_remap_all.cold (STB_LOCAL)
ffffffff815bdba0-ffffffff815bdbf8: fbcon_remap_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void fbcon_remap_all(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:3173
Inline: False
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
```
**Symbols:**

```
ffffffff815d7d4b-ffffffff815d7d78: fbcon_remap_all.cold (STB_LOCAL)
ffffffff815d7660-ffffffff815d76f7: fbcon_remap_all (STB_GLOBAL)
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
