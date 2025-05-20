# Function: <code>register_framebuffer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int register_framebuffer(struct fb_info *fb_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff8146dc40)
Location: drivers/video/fbdev/core/fbmem.c:1772
Inline: False
Direct callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
**Symbols:**

```
ffffffff8146dc40-ffffffff8146df8a: register_framebuffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int register_framebuffer(struct fb_info *fb_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff814bbf80)
Location: drivers/video/fbdev/core/fbmem.c:1780
Inline: False
Direct callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
**Symbols:**

```
ffffffff814bbf80-ffffffff814bc2e0: register_framebuffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int register_framebuffer(struct fb_info *fb_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff814ddf80)
Location: drivers/video/fbdev/core/fbmem.c:1780
Inline: False
Direct callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
**Symbols:**

```
ffffffff814ddf80-ffffffff814de2e0: register_framebuffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int register_framebuffer(struct fb_info *fb_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff814e9530)
Location: drivers/video/fbdev/core/fbmem.c:1788
Inline: False
Direct callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/efifb.c:efifb_probe
```
**Symbols:**

```
ffffffff814e9530-ffffffff814e9885: register_framebuffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int register_framebuffer(struct fb_info *fb_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff8151e070)
Location: drivers/video/fbdev/core/fbmem.c:1801
Inline: False
Direct callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/efifb.c:efifb_probe
```
**Symbols:**

```
ffffffff8151e070-ffffffff8151e3c5: register_framebuffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int register_framebuffer(struct fb_info *fb_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (0)
Location: drivers/video/fbdev/core/fbmem.c:1815
Inline: False
Direct callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
**Symbols:**

```
ffffffff81554b99-ffffffff81554bbb: register_framebuffer.cold.15 (STB_LOCAL)
ffffffff81553c30-ffffffff81553f71: register_framebuffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int register_framebuffer(struct fb_info *fb_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (0)
Location: drivers/video/fbdev/core/fbmem.c:1910
Inline: False
Direct callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
**Symbols:**

```
ffffffff8156c4d9-ffffffff8156c4fb: register_framebuffer.cold.16 (STB_LOCAL)
ffffffff8156b410-ffffffff8156b753: register_framebuffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int register_framebuffer(struct fb_info *fb_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (0)
Location: drivers/video/fbdev/core/fbmem.c:1833
Inline: False
Direct callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
**Symbols:**

```
ffffffff8159c9a0-ffffffff8159c9e7: register_framebuffer.cold (STB_LOCAL)
ffffffff8159b930-ffffffff8159bc3a: register_framebuffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int register_framebuffer(struct fb_info *fb_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (0)
Location: drivers/video/fbdev/core/fbmem.c:1823
Inline: False
Direct callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
**Symbols:**

```
ffffffff815bdd47-ffffffff815bdd8e: register_framebuffer.cold (STB_LOCAL)
ffffffff815bcf30-ffffffff815bd23a: register_framebuffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int register_framebuffer(struct fb_info *fb_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff816670a0)
Location: drivers/video/fbdev/core/fbmem.c:1823
Inline: False
Direct callers:
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/asiliantfb.c:init_asiliant
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
**Symbols:**

```
ffffffff816670a0-ffffffff816670da: register_framebuffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int register_framebuffer(struct fb_info *fb_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff81687c80)
Location: drivers/video/fbdev/core/fbmem.c:1816
Inline: False
Direct callers:
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/asiliantfb.c:init_asiliant
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
**Symbols:**

```
ffffffff81687c80-ffffffff81687cba: register_framebuffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int register_framebuffer(struct fb_info *fb_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff8166a8f0)
Location: drivers/video/fbdev/core/fbmem.c:1814
Inline: False
Direct callers:
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
**Symbols:**

```
ffffffff8166a8f0-ffffffff8166a92a: register_framebuffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int register_framebuffer(struct fb_info *fb_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff816debf0)
Location: drivers/video/fbdev/core/fbmem.c:1867
Inline: False
Direct callers:
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/efifb.c:efifb_probe
```
**Symbols:**

```
ffffffff816debf0-ffffffff816dec2a: register_framebuffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int register_framebuffer(struct fb_info *fb_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff81808a00)
Location: drivers/video/fbdev/core/fbmem.c:1848
Inline: False
Direct callers:
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/efifb.c:efifb_probe
```
**Symbols:**

```
ffffffff81808a00-ffffffff81808a3d: register_framebuffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int register_framebuffer(struct fb_info *fb_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff819376c0)
Location: drivers/video/fbdev/core/fbmem.c:1696
Inline: False
Direct callers:
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/efifb.c:efifb_probe
```
**Symbols:**

```
ffffffff819376c0-ffffffff8193776e: register_framebuffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int register_framebuffer(struct fb_info *fb_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff8197ab80)
Location: drivers/video/fbdev/core/fbmem.c:1566
Inline: False
Direct callers:
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/efifb.c:efifb_probe
```
**Symbols:**

```
ffffffff8197ab80-ffffffff8197abbd: register_framebuffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int register_framebuffer(struct fb_info *fb_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff819c42b0)
Location: drivers/video/fbdev/core/fbmem.c:510
Inline: False
Direct callers:
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/gpu/drm/drm_fb_helper.c:__drm_fb_helper_initial_config_and_unlock
```
**Symbols:**

```
ffffffff819c42b0-ffffffff819c42ed: register_framebuffer (STB_GLOBAL)
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
int register_framebuffer(struct fb_info *fb_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffff800010743c20)
Location: drivers/video/fbdev/core/fbmem.c:1823
Inline: False
Direct callers:
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/amba-clcd.c:clcdfb_register
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
**Symbols:**

```
ffff800010743c20-ffff800010743f58: register_framebuffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int register_framebuffer(struct fb_info *fb_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (c08c7e14)
Location: drivers/video/fbdev/core/fbmem.c:1823
Inline: False
Direct callers:
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/amba-clcd.c:clcdfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
**Symbols:**

```
c08c7e14-c08c810c: register_framebuffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int register_framebuffer(struct fb_info *fb_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (c0000000008a4ee0)
Location: drivers/video/fbdev/core/fbmem.c:1823
Inline: False
Direct callers:
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/gxt4500.c:gxt4500_probe
  - drivers/video/fbdev/offb.c:offb_init_fb
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
**Symbols:**

```
c0000000008a4ee0-c0000000008a5360: register_framebuffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int register_framebuffer(struct fb_info *fb_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffe0004f46e0)
Location: drivers/video/fbdev/core/fbmem.c:1823
Inline: False
Direct callers:
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
**Symbols:**

```
ffffffe0004f46e0-ffffffe0004f495e: register_framebuffer (STB_GLOBAL)
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
int register_framebuffer(struct fb_info *fb_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (0)
Location: drivers/video/fbdev/core/fbmem.c:1823
Inline: False
Direct callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
**Symbols:**

```
ffffffff815b1e97-ffffffff815b1ede: register_framebuffer.cold (STB_LOCAL)
ffffffff815b1080-ffffffff815b138a: register_framebuffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int register_framebuffer(struct fb_info *fb_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (0)
Location: drivers/video/fbdev/core/fbmem.c:1823
Inline: False
```
**Symbols:**

```
ffffffff815a1027-ffffffff815a106e: register_framebuffer.cold (STB_LOCAL)
ffffffff815a0210-ffffffff815a051a: register_framebuffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int register_framebuffer(struct fb_info *fb_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (0)
Location: drivers/video/fbdev/core/fbmem.c:1823
Inline: False
Direct callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
**Symbols:**

```
ffffffff815b2427-ffffffff815b246e: register_framebuffer.cold (STB_LOCAL)
ffffffff815b1610-ffffffff815b191a: register_framebuffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int register_framebuffer(struct fb_info *fb_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (0)
Location: drivers/video/fbdev/core/fbmem.c:1823
Inline: False
Direct callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
**Symbols:**

```
ffffffff815cbe97-ffffffff815cbede: register_framebuffer.cold (STB_LOCAL)
ffffffff815cb080-ffffffff815cb38a: register_framebuffer (STB_GLOBAL)
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
