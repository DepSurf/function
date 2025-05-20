# Function: <code>fbcon_resumed</code>

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
In drivers/video/console/fbcon.c (ffffffff81465b4d)
Location: drivers/video/console/fbcon.c:2878
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
In drivers/video/console/fbcon.c (ffffffff814b3e1f)
Location: drivers/video/console/fbcon.c:2876
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
In drivers/video/console/fbcon.c (ffffffff814d5e4f)
Location: drivers/video/console/fbcon.c:2887
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
In drivers/video/console/fbcon.c (ffffffff814e1182)
Location: drivers/video/console/fbcon.c:2885
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
In drivers/video/fbdev/core/fbcon.c (ffffffff8152ae38)
Location: drivers/video/fbdev/core/fbcon.c:2901
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
In drivers/video/fbdev/core/fbcon.c (ffffffff8155fae8)
Location: drivers/video/fbdev/core/fbcon.c:2909
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
In drivers/video/fbdev/core/fbcon.c (ffffffff8157837d)
Location: drivers/video/fbdev/core/fbcon.c:2928
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
void fbcon_resumed(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815a82e0)
Location: drivers/video/fbdev/core/fbcon.c:2945
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
```
**Symbols:**

```
ffffffff815a82e0-ffffffff815a8316: fbcon_resumed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fbcon_resumed(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815c91d0)
Location: drivers/video/fbdev/core/fbcon.c:2945
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
```
**Symbols:**

```
ffffffff815c91d0-ffffffff815c9206: fbcon_resumed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fbcon_resumed(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff81672a70)
Location: drivers/video/fbdev/core/fbcon.c:2656
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
```
**Symbols:**

```
ffffffff81672a70-ffffffff81672aa6: fbcon_resumed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fbcon_resumed(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff81692e30)
Location: drivers/video/fbdev/core/fbcon.c:2613
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
```
**Symbols:**

```
ffffffff81692e30-ffffffff81692e66: fbcon_resumed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fbcon_resumed(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff81675c00)
Location: drivers/video/fbdev/core/fbcon.c:2605
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
```
**Symbols:**

```
ffffffff81675c00-ffffffff81675c36: fbcon_resumed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fbcon_resumed(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff816ea390)
Location: drivers/video/fbdev/core/fbcon.c:2650
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
```
**Symbols:**

```
ffffffff816ea390-ffffffff816ea3e9: fbcon_resumed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fbcon_resumed(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff818157b0)
Location: drivers/video/fbdev/core/fbcon.c:2665
Inline: False
```
**Symbols:**

```
ffffffff818157b0-ffffffff8181581d: fbcon_resumed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fbcon_resumed(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff81944990)
Location: drivers/video/fbdev/core/fbcon.c:2663
Inline: False
```
**Symbols:**

```
ffffffff81944990-ffffffff819449fd: fbcon_resumed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fbcon_resumed(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff81988fd0)
Location: drivers/video/fbdev/core/fbcon.c:2656
Inline: False
```
**Symbols:**

```
ffffffff81988fd0-ffffffff8198903d: fbcon_resumed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fbcon_resumed(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff819d2ec0)
Location: drivers/video/fbdev/core/fbcon.c:2656
Inline: False
```
**Symbols:**

```
ffffffff819d2ec0-ffffffff819d2f2d: fbcon_resumed (STB_GLOBAL)
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
void fbcon_resumed(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffff800010752528)
Location: drivers/video/fbdev/core/fbcon.c:2945
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
```
**Symbols:**

```
ffff800010752528-ffff800010752578: fbcon_resumed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fbcon_resumed(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (c08d4d68)
Location: drivers/video/fbdev/core/fbcon.c:2945
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
```
**Symbols:**

```
c08d4d68-c08d4db4: fbcon_resumed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fbcon_resumed(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (c0000000008b61d0)
Location: drivers/video/fbdev/core/fbcon.c:2945
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
```
**Symbols:**

```
c0000000008b61d0-c0000000008b6230: fbcon_resumed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fbcon_resumed(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffe0004ff602)
Location: drivers/video/fbdev/core/fbcon.c:2945
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
```
**Symbols:**

```
ffffffe0004ff602-ffffffe0004ff64e: fbcon_resumed (STB_GLOBAL)
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
void fbcon_resumed(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815bd2d0)
Location: drivers/video/fbdev/core/fbcon.c:2945
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
```
**Symbols:**

```
ffffffff815bd2d0-ffffffff815bd306: fbcon_resumed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fbcon_resumed(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815ac0b0)
Location: drivers/video/fbdev/core/fbcon.c:2945
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
```
**Symbols:**

```
ffffffff815ac0b0-ffffffff815ac0e6: fbcon_resumed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fbcon_resumed(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815bd860)
Location: drivers/video/fbdev/core/fbcon.c:2945
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
```
**Symbols:**

```
ffffffff815bd860-ffffffff815bd896: fbcon_resumed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fbcon_resumed(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815d7310)
Location: drivers/video/fbdev/core/fbcon.c:2945
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
```
**Symbols:**

```
ffffffff815d7310-ffffffff815d7346: fbcon_resumed (STB_GLOBAL)
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
