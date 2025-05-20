# Function: <code>fbcon_suspended</code>

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
In drivers/video/console/fbcon.c (ffffffff81465b87)
Location: drivers/video/console/fbcon.c:2865
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
In drivers/video/console/fbcon.c (ffffffff814b3e59)
Location: drivers/video/console/fbcon.c:2863
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
In drivers/video/console/fbcon.c (ffffffff814d5e89)
Location: drivers/video/console/fbcon.c:2874
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
In drivers/video/console/fbcon.c (ffffffff814e11bb)
Location: drivers/video/console/fbcon.c:2872
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
In drivers/video/fbdev/core/fbcon.c (ffffffff8152ae71)
Location: drivers/video/fbdev/core/fbcon.c:2888
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
In drivers/video/fbdev/core/fbcon.c (ffffffff8155fab7)
Location: drivers/video/fbdev/core/fbcon.c:2896
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
In drivers/video/fbdev/core/fbcon.c (ffffffff8157801c)
Location: drivers/video/fbdev/core/fbcon.c:2915
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
void fbcon_suspended(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815a82a0)
Location: drivers/video/fbdev/core/fbcon.c:2932
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
```
**Symbols:**

```
ffffffff815a82a0-ffffffff815a82d9: fbcon_suspended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fbcon_suspended(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815c9190)
Location: drivers/video/fbdev/core/fbcon.c:2932
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
```
**Symbols:**

```
ffffffff815c9190-ffffffff815c91c9: fbcon_suspended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fbcon_suspended(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff81672a30)
Location: drivers/video/fbdev/core/fbcon.c:2643
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
```
**Symbols:**

```
ffffffff81672a30-ffffffff81672a69: fbcon_suspended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fbcon_suspended(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff81692df0)
Location: drivers/video/fbdev/core/fbcon.c:2600
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
```
**Symbols:**

```
ffffffff81692df0-ffffffff81692e29: fbcon_suspended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fbcon_suspended(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff81675bc0)
Location: drivers/video/fbdev/core/fbcon.c:2592
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
```
**Symbols:**

```
ffffffff81675bc0-ffffffff81675bf9: fbcon_suspended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fbcon_suspended(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff816ea330)
Location: drivers/video/fbdev/core/fbcon.c:2637
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
```
**Symbols:**

```
ffffffff816ea330-ffffffff816ea38c: fbcon_suspended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fbcon_suspended(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff81815740)
Location: drivers/video/fbdev/core/fbcon.c:2652
Inline: False
```
**Symbols:**

```
ffffffff81815740-ffffffff818157b0: fbcon_suspended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fbcon_suspended(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff81944910)
Location: drivers/video/fbdev/core/fbcon.c:2650
Inline: False
```
**Symbols:**

```
ffffffff81944910-ffffffff81944980: fbcon_suspended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fbcon_suspended(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff81988f50)
Location: drivers/video/fbdev/core/fbcon.c:2643
Inline: False
```
**Symbols:**

```
ffffffff81988f50-ffffffff81988fc0: fbcon_suspended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fbcon_suspended(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff819d2e40)
Location: drivers/video/fbdev/core/fbcon.c:2643
Inline: False
```
**Symbols:**

```
ffffffff819d2e40-ffffffff819d2eb0: fbcon_suspended (STB_GLOBAL)
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
void fbcon_suspended(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffff8000107524d8)
Location: drivers/video/fbdev/core/fbcon.c:2932
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
```
**Symbols:**

```
ffff8000107524d8-ffff800010752528: fbcon_suspended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fbcon_suspended(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (c08d4d1c)
Location: drivers/video/fbdev/core/fbcon.c:2932
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
```
**Symbols:**

```
c08d4d1c-c08d4d68: fbcon_suspended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fbcon_suspended(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (c0000000008b6190)
Location: drivers/video/fbdev/core/fbcon.c:2932
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
```
**Symbols:**

```
c0000000008b6190-c0000000008b61d0: fbcon_suspended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fbcon_suspended(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffe0004ff5b6)
Location: drivers/video/fbdev/core/fbcon.c:2932
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
```
**Symbols:**

```
ffffffe0004ff5b6-ffffffe0004ff602: fbcon_suspended (STB_GLOBAL)
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
void fbcon_suspended(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815bd290)
Location: drivers/video/fbdev/core/fbcon.c:2932
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
```
**Symbols:**

```
ffffffff815bd290-ffffffff815bd2c9: fbcon_suspended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fbcon_suspended(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815ac070)
Location: drivers/video/fbdev/core/fbcon.c:2932
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
```
**Symbols:**

```
ffffffff815ac070-ffffffff815ac0a9: fbcon_suspended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fbcon_suspended(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815bd820)
Location: drivers/video/fbdev/core/fbcon.c:2932
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
```
**Symbols:**

```
ffffffff815bd820-ffffffff815bd859: fbcon_suspended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fbcon_suspended(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815d72d0)
Location: drivers/video/fbdev/core/fbcon.c:2932
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_suspend
```
**Symbols:**

```
ffffffff815d72d0-ffffffff815d7309: fbcon_suspended (STB_GLOBAL)
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
