# Function: <code>fbcon_select_primary</code>

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
Location: drivers/video/console/fbcon.c:3115
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
Location: drivers/video/console/fbcon.c:3113
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
Location: drivers/video/console/fbcon.c:3124
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
Location: drivers/video/console/fbcon.c:3122
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
Location: drivers/video/fbdev/core/fbcon.c:3138
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
In drivers/video/fbdev/core/fbcon.c (ffffffff8155fb91)
Location: drivers/video/fbdev/core/fbcon.c:3146
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
In drivers/video/fbdev/core/fbcon.c (ffffffff815783c8)
Location: drivers/video/fbdev/core/fbcon.c:3180
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_event_notify
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
In drivers/video/fbdev/core/fbcon.c (ffffffff815a86a7)
Location: drivers/video/fbdev/core/fbcon.c:3199
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered
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
In drivers/video/fbdev/core/fbcon.c (ffffffff815c95e7)
Location: drivers/video/fbdev/core/fbcon.c:3199
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void fbcon_select_primary(struct fb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:2908
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered
```
**Symbols:**

```
ffffffff8166f110-ffffffff8166f144: fbcon_select_primary (STB_LOCAL)
ffffffff81673434-ffffffff816734b7: fbcon_select_primary.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void fbcon_select_primary(struct fb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:2865
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered
```
**Symbols:**

```
ffffffff8168f630-ffffffff8168f664: fbcon_select_primary (STB_LOCAL)
ffffffff81bff0b8-ffffffff81bff13b: fbcon_select_primary.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff81676017)
Location: drivers/video/fbdev/core/fbcon.c:2857
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff816eab2d)
Location: drivers/video/fbdev/core/fbcon.c:2902
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff81811f6a)
Location: drivers/video/fbdev/core/fbcon.c:2948
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:do_fb_registered
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff81940eee)
Location: drivers/video/fbdev/core/fbcon.c:2946
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:do_fb_registered
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff819854de)
Location: drivers/video/fbdev/core/fbcon.c:2939
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:do_fb_registered
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff819cf3fd)
Location: drivers/video/fbdev/core/fbcon.c:2939
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:do_fb_registered
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:3199
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:3199
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:3199
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:3199
Inline: True
```
</details>
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
In drivers/video/fbdev/core/fbcon.c (ffffffff815bd697)
Location: drivers/video/fbdev/core/fbcon.c:3199
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered
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
In drivers/video/fbdev/core/fbcon.c (ffffffff815ac477)
Location: drivers/video/fbdev/core/fbcon.c:3199
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered
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
In drivers/video/fbdev/core/fbcon.c (ffffffff815bdc27)
Location: drivers/video/fbdev/core/fbcon.c:3199
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered
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
In drivers/video/fbdev/core/fbcon.c (ffffffff815d7727)
Location: drivers/video/fbdev/core/fbcon.c:3199
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered
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
</ul>
