# Function: <code>unbind_console</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int unbind_console(struct fb_info *fb_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff81552f10)
Location: drivers/video/fbdev/core/fbmem.c:1707
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
```
**Symbols:**

```
ffffffff81552f10-ffffffff81552fcf: unbind_console (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int unbind_console(struct fb_info *fb_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff8156a790)
Location: drivers/video/fbdev/core/fbmem.c:1744
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
```
**Symbols:**

```
ffffffff8156a790-ffffffff8156a84f: unbind_console (STB_LOCAL)
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
In drivers/video/fbdev/core/fbmem.c (ffffffff8159aef4)
Location: drivers/video/fbdev/core/fbmem.c:1672
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
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
In drivers/video/fbdev/core/fbmem.c (ffffffff815bc2d3)
Location: drivers/video/fbdev/core/fbmem.c:1662
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
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
In drivers/video/fbdev/core/fbmem.c (ffffffff81666c99)
Location: drivers/video/fbdev/core/fbmem.c:1670
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
In drivers/video/fbdev/core/fbmem.c (ffffffff81687879)
Location: drivers/video/fbdev/core/fbmem.c:1663
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
In drivers/video/fbdev/core/fbmem.c (ffffffff8166a4e9)
Location: drivers/video/fbdev/core/fbmem.c:1661
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
In drivers/video/fbdev/core/fbmem.c (ffffffff816de39e)
Location: drivers/video/fbdev/core/fbmem.c:1667
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
In drivers/video/fbdev/core/fbmem.c (ffffffff81808366)
Location: drivers/video/fbdev/core/fbmem.c:1687
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
In drivers/video/fbdev/core/fbmem.c (ffffffff81937356)
Location: drivers/video/fbdev/core/fbmem.c:1604
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
In drivers/video/fbdev/core/fbmem.c (ffffffff8197b3f6)
Location: drivers/video/fbdev/core/fbmem.c:1500
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
In drivers/video/fbdev/core/fbmem.c (ffffffff819c4619)
Location: drivers/video/fbdev/core/fbmem.c:452
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffff800010743044)
Location: drivers/video/fbdev/core/fbmem.c:1662
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
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
In drivers/video/fbdev/core/fbmem.c (c08c7914)
Location: drivers/video/fbdev/core/fbmem.c:1662
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
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
In drivers/video/fbdev/core/fbmem.c (c0000000008a3f20)
Location: drivers/video/fbdev/core/fbmem.c:1662
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
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
In drivers/video/fbdev/core/fbmem.c (ffffffe0004f3d3e)
Location: drivers/video/fbdev/core/fbmem.c:1662
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
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
In drivers/video/fbdev/core/fbmem.c (ffffffff815b0423)
Location: drivers/video/fbdev/core/fbmem.c:1662
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
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
In drivers/video/fbdev/core/fbmem.c (ffffffff8159f5b3)
Location: drivers/video/fbdev/core/fbmem.c:1662
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
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
In drivers/video/fbdev/core/fbmem.c (ffffffff815b09b3)
Location: drivers/video/fbdev/core/fbmem.c:1662
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
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
In drivers/video/fbdev/core/fbmem.c (ffffffff815ca423)
Location: drivers/video/fbdev/core/fbmem.c:1662
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
