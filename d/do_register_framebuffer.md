# Function: <code>do_register_framebuffer</code>

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
In drivers/video/fbdev/core/fbmem.c (ffffffff8146dc74)
Location: drivers/video/fbdev/core/fbmem.c:1611
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
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
In drivers/video/fbdev/core/fbmem.c (ffffffff814bbfb4)
Location: drivers/video/fbdev/core/fbmem.c:1616
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
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
In drivers/video/fbdev/core/fbmem.c (ffffffff814ddfb4)
Location: drivers/video/fbdev/core/fbmem.c:1616
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
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
In drivers/video/fbdev/core/fbmem.c (ffffffff814e9564)
Location: drivers/video/fbdev/core/fbmem.c:1624
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
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
In drivers/video/fbdev/core/fbmem.c (ffffffff8151e0a4)
Location: drivers/video/fbdev/core/fbmem.c:1637
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
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
In drivers/video/fbdev/core/fbmem.c (ffffffff81553c6b)
Location: drivers/video/fbdev/core/fbmem.c:1625
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
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
In drivers/video/fbdev/core/fbmem.c (ffffffff8156b44b)
Location: drivers/video/fbdev/core/fbmem.c:1657
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
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
In drivers/video/fbdev/core/fbmem.c (ffffffff8159b96a)
Location: drivers/video/fbdev/core/fbmem.c:1586
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
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
In drivers/video/fbdev/core/fbmem.c (ffffffff815bcf6a)
Location: drivers/video/fbdev/core/fbmem.c:1576
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int do_register_framebuffer(struct fb_info *fb_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (0)
Location: drivers/video/fbdev/core/fbmem.c:1584
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
```
**Symbols:**

```
ffffffff81666db0-ffffffff81667098: do_register_framebuffer (STB_LOCAL)
ffffffff81667d78-ffffffff81667dbd: do_register_framebuffer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int do_register_framebuffer(struct fb_info *fb_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (0)
Location: drivers/video/fbdev/core/fbmem.c:1577
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
```
**Symbols:**

```
ffffffff81687990-ffffffff81687c78: do_register_framebuffer (STB_LOCAL)
ffffffff81bfecc6-ffffffff81bfed0b: do_register_framebuffer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int do_register_framebuffer(struct fb_info *fb_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (0)
Location: drivers/video/fbdev/core/fbmem.c:1575
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
```
**Symbols:**

```
ffffffff8166a600-ffffffff8166a8e8: do_register_framebuffer (STB_LOCAL)
ffffffff81bf0855-ffffffff81bf089a: do_register_framebuffer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int do_register_framebuffer(struct fb_info *fb_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (0)
Location: drivers/video/fbdev/core/fbmem.c:1581
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
```
**Symbols:**

```
ffffffff816de8a0-ffffffff816debed: do_register_framebuffer (STB_LOCAL)
ffffffff81cec321-ffffffff81cec3a3: do_register_framebuffer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int do_register_framebuffer(struct fb_info *fb_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (0)
Location: drivers/video/fbdev/core/fbmem.c:1613
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
```
**Symbols:**

```
ffffffff81808700-ffffffff818089fa: do_register_framebuffer (STB_LOCAL)
ffffffff81eb3905-ffffffff81eb3954: do_register_framebuffer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int do_register_framebuffer(struct fb_info *fb_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (0)
Location: drivers/video/fbdev/core/fbmem.c:1534
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
```
**Symbols:**

```
ffffffff81936810-ffffffff81936b2b: do_register_framebuffer (STB_LOCAL)
ffffffff82090700-ffffffff82090715: do_register_framebuffer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int do_register_framebuffer(struct fb_info *fb_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (0)
Location: drivers/video/fbdev/core/fbmem.c:1430
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
```
**Symbols:**

```
ffffffff8197a840-ffffffff8197ab64: do_register_framebuffer (STB_LOCAL)
ffffffff82110a15-ffffffff82110a2a: do_register_framebuffer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int do_register_framebuffer(struct fb_info *fb_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (0)
Location: drivers/video/fbdev/core/fbmem.c:389
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
```
**Symbols:**

```
ffffffff819c3fb0-ffffffff819c4296: do_register_framebuffer (STB_LOCAL)
ffffffff821ee81d-ffffffff821ee832: do_register_framebuffer.cold (STB_LOCAL)
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
In drivers/video/fbdev/core/fbmem.c (ffff800010743c60)
Location: drivers/video/fbdev/core/fbmem.c:1576
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
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
In drivers/video/fbdev/core/fbmem.c (c08c7e50)
Location: drivers/video/fbdev/core/fbmem.c:1576
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
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
In drivers/video/fbdev/core/fbmem.c (c0000000008a4f30)
Location: drivers/video/fbdev/core/fbmem.c:1576
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
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
In drivers/video/fbdev/core/fbmem.c (ffffffe0004f470e)
Location: drivers/video/fbdev/core/fbmem.c:1576
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
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
In drivers/video/fbdev/core/fbmem.c (ffffffff815b10ba)
Location: drivers/video/fbdev/core/fbmem.c:1576
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
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
In drivers/video/fbdev/core/fbmem.c (ffffffff815a024a)
Location: drivers/video/fbdev/core/fbmem.c:1576
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
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
In drivers/video/fbdev/core/fbmem.c (ffffffff815b164a)
Location: drivers/video/fbdev/core/fbmem.c:1576
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
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
In drivers/video/fbdev/core/fbmem.c (ffffffff815cb0ba)
Location: drivers/video/fbdev/core/fbmem.c:1576
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
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
