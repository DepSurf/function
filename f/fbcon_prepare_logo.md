# Function: <code>fbcon_prepare_logo</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void fbcon_prepare_logo(struct vc_data *vc, struct fb_info *info, int cols, int rows, int new_cols, int new_rows);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/console/fbcon.c (ffffffff81460fe0)
Location: drivers/video/console/fbcon.c:562
Inline: False
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_init
  - drivers/video/console/fbcon.c:set_con2fb_map
```
**Symbols:**

```
ffffffff81460fe0-ffffffff814613d8: fbcon_prepare_logo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void fbcon_prepare_logo(struct vc_data *vc, struct fb_info *info, int cols, int rows, int new_cols, int new_rows);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/console/fbcon.c (ffffffff814aef20)
Location: drivers/video/console/fbcon.c:561
Inline: False
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_init
  - drivers/video/console/fbcon.c:set_con2fb_map
```
**Symbols:**

```
ffffffff814aef20-ffffffff814af337: fbcon_prepare_logo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void fbcon_prepare_logo(struct vc_data *vc, struct fb_info *info, int cols, int rows, int new_cols, int new_rows);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/console/fbcon.c (ffffffff814d1030)
Location: drivers/video/console/fbcon.c:559
Inline: False
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_init
  - drivers/video/console/fbcon.c:set_con2fb_map
```
**Symbols:**

```
ffffffff814d1030-ffffffff814d1447: fbcon_prepare_logo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void fbcon_prepare_logo(struct vc_data *vc, struct fb_info *info, int cols, int rows, int new_cols, int new_rows);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/console/fbcon.c (ffffffff814dd910)
Location: drivers/video/console/fbcon.c:557
Inline: False
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_init
  - drivers/video/console/fbcon.c:set_con2fb_map
```
**Symbols:**

```
ffffffff814dd910-ffffffff814ddd46: fbcon_prepare_logo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void fbcon_prepare_logo(struct vc_data *vc, struct fb_info *info, int cols, int rows, int new_cols, int new_rows);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff81529d00)
Location: drivers/video/fbdev/core/fbcon.c:565
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
```
**Symbols:**

```
ffffffff81529d00-ffffffff8152a0c5: fbcon_prepare_logo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void fbcon_prepare_logo(struct vc_data *vc, struct fb_info *info, int cols, int rows, int new_cols, int new_rows);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:565
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
```
**Symbols:**

```
ffffffff8155d490-ffffffff8155d85a: fbcon_prepare_logo (STB_LOCAL)
ffffffff81560caf-ffffffff81560cca: fbcon_prepare_logo.cold.32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void fbcon_prepare_logo(struct vc_data *vc, struct fb_info *info, int cols, int rows, int new_cols, int new_rows);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:583
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
```
**Symbols:**

```
ffffffff81577180-ffffffff81577587: fbcon_prepare_logo (STB_LOCAL)
ffffffff815786d2-ffffffff815786ed: fbcon_prepare_logo.cold.32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void fbcon_prepare_logo(struct vc_data *vc, struct fb_info *info, int cols, int rows, int new_cols, int new_rows);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:602
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
```
**Symbols:**

```
ffffffff815a7330-ffffffff815a7735: fbcon_prepare_logo (STB_LOCAL)
ffffffff815a8be3-ffffffff815a8bfe: fbcon_prepare_logo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void fbcon_prepare_logo(struct vc_data *vc, struct fb_info *info, int cols, int rows, int new_cols, int new_rows);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:602
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
```
**Symbols:**

```
ffffffff815c8200-ffffffff815c8605: fbcon_prepare_logo (STB_LOCAL)
ffffffff815c9bbb-ffffffff815c9bd6: fbcon_prepare_logo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void fbcon_prepare_logo(struct vc_data *vc, struct fb_info *info, int cols, int rows, int new_cols, int new_rows);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:583
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
```
**Symbols:**

```
ffffffff81670f70-ffffffff8167136c: fbcon_prepare_logo (STB_LOCAL)
ffffffff816734be-ffffffff816734d9: fbcon_prepare_logo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void fbcon_prepare_logo(struct vc_data *vc, struct fb_info *info, int cols, int rows, int new_cols, int new_rows);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:581
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
```
**Symbols:**

```
ffffffff816913b0-ffffffff816917d9: fbcon_prepare_logo (STB_LOCAL)
ffffffff81bff142-ffffffff81bff15d: fbcon_prepare_logo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void fbcon_prepare_logo(struct vc_data *vc, struct fb_info *info, int cols, int rows, int new_cols, int new_rows);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:573
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
```
**Symbols:**

```
ffffffff81674030-ffffffff81674447: fbcon_prepare_logo (STB_LOCAL)
ffffffff81bf0bb4-ffffffff81bf0bcf: fbcon_prepare_logo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void fbcon_prepare_logo(struct vc_data *vc, struct fb_info *info, int cols, int rows, int new_cols, int new_rows);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:573
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
```
**Symbols:**

```
ffffffff816e8120-ffffffff816e8535: fbcon_prepare_logo (STB_LOCAL)
ffffffff81cec742-ffffffff81cec75d: fbcon_prepare_logo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void fbcon_prepare_logo(struct vc_data *vc, struct fb_info *info, int cols, int rows, int new_cols, int new_rows);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:551
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
```
**Symbols:**

```
ffffffff818113b0-ffffffff81811839: fbcon_prepare_logo (STB_LOCAL)
ffffffff81eb3b9d-ffffffff81eb3bb8: fbcon_prepare_logo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fbcon_prepare_logo(struct vc_data *vc, struct fb_info *info, int cols, int rows, int new_cols, int new_rows);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff819402d0)
Location: drivers/video/fbdev/core/fbcon.c:551
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
```
**Symbols:**

```
ffffffff819402d0-ffffffff8194076a: fbcon_prepare_logo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fbcon_prepare_logo(struct vc_data *vc, struct fb_info *info, int cols, int rows, int new_cols, int new_rows);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff819847e0)
Location: drivers/video/fbdev/core/fbcon.c:550
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
```
**Symbols:**

```
ffffffff819847e0-ffffffff81984cd4: fbcon_prepare_logo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fbcon_prepare_logo(struct vc_data *vc, struct fb_info *info, int cols, int rows, int new_cols, int new_rows);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff819ce720)
Location: drivers/video/fbdev/core/fbcon.c:553
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
```
**Symbols:**

```
ffffffff819ce720-ffffffff819cebf6: fbcon_prepare_logo (STB_LOCAL)
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
void fbcon_prepare_logo(struct vc_data *vc, struct fb_info *info, int cols, int rows, int new_cols, int new_rows);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffff8000107517f0)
Location: drivers/video/fbdev/core/fbcon.c:602
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
```
**Symbols:**

```
ffff8000107517f0-ffff800010751bf8: fbcon_prepare_logo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fbcon_prepare_logo(struct vc_data *vc, struct fb_info *info, int cols, int rows, int new_cols, int new_rows);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (c08d3d1c)
Location: drivers/video/fbdev/core/fbcon.c:602
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
```
**Symbols:**

```
c08d3d1c-c08d4134: fbcon_prepare_logo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fbcon_prepare_logo(struct vc_data *vc, struct fb_info *info, int cols, int rows, int new_cols, int new_rows);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (c0000000008b2d50)
Location: drivers/video/fbdev/core/fbcon.c:602
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
```
**Symbols:**

```
c0000000008b2d50-c0000000008b32e4: fbcon_prepare_logo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fbcon_prepare_logo(struct vc_data *vc, struct fb_info *info, int cols, int rows, int new_cols, int new_rows);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffe0004fd1dc)
Location: drivers/video/fbdev/core/fbcon.c:602
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
```
**Symbols:**

```
ffffffe0004fd1dc-ffffffe0004fd5c6: fbcon_prepare_logo (STB_LOCAL)
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
void fbcon_prepare_logo(struct vc_data *vc, struct fb_info *info, int cols, int rows, int new_cols, int new_rows);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:602
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
```
**Symbols:**

```
ffffffff815bc300-ffffffff815bc705: fbcon_prepare_logo (STB_LOCAL)
ffffffff815bdbd3-ffffffff815bdbee: fbcon_prepare_logo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void fbcon_prepare_logo(struct vc_data *vc, struct fb_info *info, int cols, int rows, int new_cols, int new_rows);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:602
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
```
**Symbols:**

```
ffffffff815ab0e0-ffffffff815ab4e5: fbcon_prepare_logo (STB_LOCAL)
ffffffff815ac9b3-ffffffff815ac9ce: fbcon_prepare_logo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void fbcon_prepare_logo(struct vc_data *vc, struct fb_info *info, int cols, int rows, int new_cols, int new_rows);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:602
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
```
**Symbols:**

```
ffffffff815bc890-ffffffff815bcc95: fbcon_prepare_logo (STB_LOCAL)
ffffffff815be163-ffffffff815be17e: fbcon_prepare_logo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void fbcon_prepare_logo(struct vc_data *vc, struct fb_info *info, int cols, int rows, int new_cols, int new_rows);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:602
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
```
**Symbols:**

```
ffffffff815d6340-ffffffff815d6745: fbcon_prepare_logo (STB_LOCAL)
ffffffff815d7cfb-ffffffff815d7d16: fbcon_prepare_logo.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
