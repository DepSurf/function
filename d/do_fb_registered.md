# Function: <code>do_fb_registered</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int do_fb_registered(struct fb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:2983
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered
```
**Symbols:**

```
ffffffff81811f20-ffffffff818120c4: do_fb_registered (STB_LOCAL)
ffffffff81eb3c18-ffffffff81eb3cd9: do_fb_registered.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int do_fb_registered(struct fb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:2981
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered
```
**Symbols:**

```
ffffffff81940ea0-ffffffff81941109: do_fb_registered (STB_LOCAL)
ffffffff8209079e-ffffffff820907b2: do_fb_registered.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int do_fb_registered(struct fb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:2974
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered
```
**Symbols:**

```
ffffffff81985490-ffffffff819856f9: do_fb_registered (STB_LOCAL)
ffffffff82110aa5-ffffffff82110ab9: do_fb_registered.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int do_fb_registered(struct fb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:2974
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered
```
**Symbols:**

```
ffffffff819cf3b0-ffffffff819cf618: do_fb_registered (STB_LOCAL)
ffffffff821ee8d7-ffffffff821ee8eb: do_fb_registered.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
