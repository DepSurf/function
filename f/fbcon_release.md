# Function: <code>fbcon_release</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
void fbcon_release(struct fb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff8180ff90)
Location: drivers/video/fbdev/core/fbcon.c:684
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/video/fbdev/core/fbcon.c:fbcon_open
```
**Symbols:**

```
ffffffff8180ff90-ffffffff8181004f: fbcon_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fbcon_release(struct fb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff8193ebc0)
Location: drivers/video/fbdev/core/fbcon.c:684
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/video/fbdev/core/fbcon.c:fbcon_open
```
**Symbols:**

```
ffffffff8193ebc0-ffffffff8193ec7f: fbcon_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fbcon_release(struct fb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff81983080)
Location: drivers/video/fbdev/core/fbcon.c:683
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/video/fbdev/core/fbcon.c:fbcon_open
```
**Symbols:**

```
ffffffff81983080-ffffffff8198313f: fbcon_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fbcon_release(struct fb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff819ccf90)
Location: drivers/video/fbdev/core/fbcon.c:685
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/video/fbdev/core/fbcon.c:fbcon_open
```
**Symbols:**

```
ffffffff819ccf90-ffffffff819cd04f: fbcon_release (STB_LOCAL)
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
