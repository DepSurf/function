# Function: <code>unlink_framebuffer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int unlink_framebuffer(struct fb_info *fb_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff8146c850)
Location: drivers/video/fbdev/core/fbmem.c:1733
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
```
**Symbols:**

```
ffffffff8146c850-ffffffff8146c8b4: unlink_framebuffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int unlink_framebuffer(struct fb_info *fb_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff814baba0)
Location: drivers/video/fbdev/core/fbmem.c:1741
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
```
**Symbols:**

```
ffffffff814baba0-ffffffff814bac04: unlink_framebuffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int unlink_framebuffer(struct fb_info *fb_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff814dcba0)
Location: drivers/video/fbdev/core/fbmem.c:1741
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
```
**Symbols:**

```
ffffffff814dcba0-ffffffff814dcc04: unlink_framebuffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int unlink_framebuffer(struct fb_info *fb_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff814e8740)
Location: drivers/video/fbdev/core/fbmem.c:1749
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
```
**Symbols:**

```
ffffffff814e8740-ffffffff814e87a4: unlink_framebuffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int unlink_framebuffer(struct fb_info *fb_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff8151d230)
Location: drivers/video/fbdev/core/fbmem.c:1762
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
```
**Symbols:**

```
ffffffff8151d230-ffffffff8151d294: unlink_framebuffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int unlink_framebuffer(struct fb_info *fb_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff81552fd0)
Location: drivers/video/fbdev/core/fbmem.c:1778
Inline: False
```
**Symbols:**

```
ffffffff81552fd0-ffffffff81552ff9: unlink_framebuffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int unlink_framebuffer(struct fb_info *fb_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff8156a850)
Location: drivers/video/fbdev/core/fbmem.c:1815
Inline: False
```
**Symbols:**

```
ffffffff8156a850-ffffffff8156a879: unlink_framebuffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void unlink_framebuffer(struct fb_info *fb_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (0)
Location: drivers/video/fbdev/core/fbmem.c:1686
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
```
**Symbols:**

```
ffffffff8159c870-ffffffff8159c896: unlink_framebuffer.cold (STB_LOCAL)
ffffffff8159aea0-ffffffff8159af45: unlink_framebuffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void unlink_framebuffer(struct fb_info *fb_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff815bc280)
Location: drivers/video/fbdev/core/fbmem.c:1676
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
```
**Symbols:**

```
ffffffff815bc280-ffffffff815bc32b: unlink_framebuffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff81666be5)
Location: drivers/video/fbdev/core/fbmem.c:1684
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff816877c5)
Location: drivers/video/fbdev/core/fbmem.c:1677
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
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
In drivers/video/fbdev/core/fbmem.c (ffffffff8166a435)
Location: drivers/video/fbdev/core/fbmem.c:1675
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
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
In drivers/video/fbdev/core/fbmem.c (ffffffff816de2c5)
Location: drivers/video/fbdev/core/fbmem.c:1681
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
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
In drivers/video/fbdev/core/fbmem.c (ffffffff81808295)
Location: drivers/video/fbdev/core/fbmem.c:1697
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
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
In drivers/video/fbdev/core/fbmem.c (ffffffff81937281)
Location: drivers/video/fbdev/core/fbmem.c:1614
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:unregister_framebuffer
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
In drivers/video/fbdev/core/fbmem.c (ffffffff8197b321)
Location: drivers/video/fbdev/core/fbmem.c:1510
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:unregister_framebuffer
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
In drivers/video/fbdev/core/fbmem.c (ffffffff819c455f)
Location: drivers/video/fbdev/core/fbmem.c:462
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:unregister_framebuffer
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
void unlink_framebuffer(struct fb_info *fb_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffff800010742fd8)
Location: drivers/video/fbdev/core/fbmem.c:1676
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
```
**Symbols:**

```
ffff800010742fd8-ffff80001074309c: unlink_framebuffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void unlink_framebuffer(struct fb_info *fb_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (c08c7898)
Location: drivers/video/fbdev/core/fbmem.c:1676
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
```
**Symbols:**

```
c08c7898-c08c7978: unlink_framebuffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void unlink_framebuffer(struct fb_info *fb_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (c0000000008a3e70)
Location: drivers/video/fbdev/core/fbmem.c:1676
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
```
**Symbols:**

```
c0000000008a3e70-c0000000008a3fa4: unlink_framebuffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void unlink_framebuffer(struct fb_info *fb_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffe0004f3cdc)
Location: drivers/video/fbdev/core/fbmem.c:1676
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
```
**Symbols:**

```
ffffffe0004f3cdc-ffffffe0004f3d9a: unlink_framebuffer (STB_GLOBAL)
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
void unlink_framebuffer(struct fb_info *fb_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff815b03d0)
Location: drivers/video/fbdev/core/fbmem.c:1676
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
```
**Symbols:**

```
ffffffff815b03d0-ffffffff815b047b: unlink_framebuffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void unlink_framebuffer(struct fb_info *fb_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff8159f560)
Location: drivers/video/fbdev/core/fbmem.c:1676
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
```
**Symbols:**

```
ffffffff8159f560-ffffffff8159f60b: unlink_framebuffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void unlink_framebuffer(struct fb_info *fb_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff815b0960)
Location: drivers/video/fbdev/core/fbmem.c:1676
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
```
**Symbols:**

```
ffffffff815b0960-ffffffff815b0a0b: unlink_framebuffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void unlink_framebuffer(struct fb_info *fb_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff815ca3d0)
Location: drivers/video/fbdev/core/fbmem.c:1676
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
```
**Symbols:**

```
ffffffff815ca3d0-ffffffff815ca47b: unlink_framebuffer (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
