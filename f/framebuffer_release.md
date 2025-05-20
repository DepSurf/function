# Function: <code>framebuffer_release</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void framebuffer_release(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff81470ff0)
Location: drivers/video/fbdev/core/fbsysfs.c:81
Inline: False
Direct callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_remove
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/efifb.c:efifb_remove
  - drivers/video/fbdev/simplefb.c:simplefb_remove
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
**Symbols:**

```
ffffffff81470ff0-ffffffff8147101a: framebuffer_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void framebuffer_release(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff814bf490)
Location: drivers/video/fbdev/core/fbsysfs.c:81
Inline: False
Direct callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_remove
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/efifb.c:efifb_remove
  - drivers/video/fbdev/simplefb.c:simplefb_remove
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
**Symbols:**

```
ffffffff814bf490-ffffffff814bf4ba: framebuffer_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void framebuffer_release(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff814e1480)
Location: drivers/video/fbdev/core/fbsysfs.c:81
Inline: False
Direct callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_remove
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/efifb.c:efifb_remove
  - drivers/video/fbdev/simplefb.c:simplefb_remove
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
**Symbols:**

```
ffffffff814e1480-ffffffff814e14aa: framebuffer_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void framebuffer_release(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff814ede40)
Location: drivers/video/fbdev/core/fbsysfs.c:81
Inline: True
Direct callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_remove
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/efifb.c:efifb_remove
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_remove
```
**Symbols:**

```
ffffffff814ede40-ffffffff814ede6b: framebuffer_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void framebuffer_release(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff815229c0)
Location: drivers/video/fbdev/core/fbsysfs.c:81
Inline: True
Direct callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_remove
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/efifb.c:efifb_remove
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_remove
```
**Symbols:**

```
ffffffff815229c0-ffffffff815229eb: framebuffer_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void framebuffer_release(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff81558630)
Location: drivers/video/fbdev/core/fbsysfs.c:82
Inline: True
Direct callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_remove
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/efifb.c:efifb_remove
  - drivers/video/fbdev/simplefb.c:simplefb_remove
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
**Symbols:**

```
ffffffff81558630-ffffffff8155865a: framebuffer_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void framebuffer_release(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff8156ffc0)
Location: drivers/video/fbdev/core/fbsysfs.c:82
Inline: True
Direct callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_remove
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/efifb.c:efifb_remove
  - drivers/video/fbdev/simplefb.c:simplefb_remove
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
**Symbols:**

```
ffffffff8156ffc0-ffffffff8156ffea: framebuffer_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void framebuffer_release(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff815a0490)
Location: drivers/video/fbdev/core/fbsysfs.c:79
Inline: True
Direct callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_remove
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/efifb.c:efifb_remove
  - drivers/video/fbdev/simplefb.c:simplefb_remove
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
**Symbols:**

```
ffffffff815a0490-ffffffff815a04bc: framebuffer_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void framebuffer_release(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff815c1310)
Location: drivers/video/fbdev/core/fbsysfs.c:79
Inline: True
Direct callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_remove
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/efifb.c:efifb_remove
  - drivers/video/fbdev/simplefb.c:simplefb_remove
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
**Symbols:**

```
ffffffff815c1310-ffffffff815c133c: framebuffer_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void framebuffer_release(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff8166b3c0)
Location: drivers/video/fbdev/core/fbsysfs.c:79
Inline: True
Direct callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_remove
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/efifb.c:efifb_remove
  - drivers/video/fbdev/simplefb.c:simplefb_remove
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
**Symbols:**

```
ffffffff8166b3c0-ffffffff8166b3ee: framebuffer_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void framebuffer_release(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff8168bd10)
Location: drivers/video/fbdev/core/fbsysfs.c:79
Inline: True
Direct callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_remove
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/efifb.c:efifb_remove
  - drivers/video/fbdev/simplefb.c:simplefb_remove
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
**Symbols:**

```
ffffffff8168bd10-ffffffff8168bd3e: framebuffer_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void framebuffer_release(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff8166e9f0)
Location: drivers/video/fbdev/core/fbsysfs.c:79
Inline: True
Direct callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_remove
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/efifb.c:efifb_remove
  - drivers/video/fbdev/simplefb.c:simplefb_remove
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
**Symbols:**

```
ffffffff8166e9f0-ffffffff8166ea1e: framebuffer_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void framebuffer_release(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff816e2bc0)
Location: drivers/video/fbdev/core/fbsysfs.c:79
Inline: True
Direct callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_remove
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/efifb.c:efifb_remove
  - drivers/video/fbdev/efifb.c:efifb_probe
```
**Symbols:**

```
ffffffff816e2bc0-ffffffff816e2bee: framebuffer_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void framebuffer_release(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff8180c0f0)
Location: drivers/video/fbdev/core/fbsysfs.c:79
Inline: False
Direct callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/video/fbdev/efifb.c:efifb_destroy
```
**Symbols:**

```
ffffffff8180c0f0-ffffffff8180c137: framebuffer_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void framebuffer_release(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff8193aad0)
Location: drivers/video/fbdev/core/fbsysfs.c:79
Inline: False
Direct callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/video/fbdev/efifb.c:efifb_destroy
```
**Symbols:**

```
ffffffff8193aad0-ffffffff8193ab17: framebuffer_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void framebuffer_release(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff8197ead0)
Location: drivers/video/fbdev/core/fbsysfs.c:79
Inline: False
Direct callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/video/fbdev/efifb.c:efifb_destroy
```
**Symbols:**

```
ffffffff8197ead0-ffffffff8197eb07: framebuffer_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void framebuffer_release(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fb_info.c (ffffffff819c3530)
Location: drivers/video/fbdev/core/fb_info.c:65
Inline: False
Direct callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/gpu/drm/drm_fb_helper.c:drm_fb_helper_alloc_info
```
**Symbols:**

```
ffffffff819c3530-ffffffff819c3567: framebuffer_release (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void framebuffer_release(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbsysfs.c (ffff80001074a188)
Location: drivers/video/fbdev/core/fbsysfs.c:79
Inline: True
Direct callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/efifb.c:efifb_remove
  - drivers/video/fbdev/mx3fb.c:mx3fb_remove
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_remove
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
**Symbols:**

```
ffff80001074a188-ffff80001074a1c0: framebuffer_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void framebuffer_release(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbsysfs.c (c08ccb58)
Location: drivers/video/fbdev/core/fbsysfs.c:79
Inline: True
Direct callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/efifb.c:efifb_remove
  - drivers/video/fbdev/mx3fb.c:mx3fb_remove
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_remove
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
**Symbols:**

```
c08ccb58-c08ccb88: framebuffer_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void framebuffer_release(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbsysfs.c (c0000000008ab740)
Location: drivers/video/fbdev/core/fbsysfs.c:79
Inline: True
Direct callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/gxt4500.c:gxt4500_remove
  - drivers/video/fbdev/gxt4500.c:gxt4500_probe
  - drivers/video/fbdev/offb.c:offb_init_fb
  - drivers/video/fbdev/offb.c:offb_destroy
  - drivers/video/fbdev/simplefb.c:simplefb_remove
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
**Symbols:**

```
c0000000008ab740-c0000000008ab794: framebuffer_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void framebuffer_release(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbsysfs.c (ffffffe0004f8404)
Location: drivers/video/fbdev/core/fbsysfs.c:79
Inline: True
Direct callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/simplefb.c:simplefb_remove
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
**Symbols:**

```
ffffffe0004f8404-ffffffe0004f843c: framebuffer_release (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void framebuffer_release(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff815b5460)
Location: drivers/video/fbdev/core/fbsysfs.c:79
Inline: True
Direct callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_remove
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/efifb.c:efifb_remove
  - drivers/video/fbdev/simplefb.c:simplefb_remove
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
**Symbols:**

```
ffffffff815b5460-ffffffff815b548c: framebuffer_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void framebuffer_release(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff815a4260)
Location: drivers/video/fbdev/core/fbsysfs.c:79
Inline: True
```
**Symbols:**

```
ffffffff815a4260-ffffffff815a428c: framebuffer_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void framebuffer_release(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff815b59f0)
Location: drivers/video/fbdev/core/fbsysfs.c:79
Inline: True
Direct callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_remove
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/efifb.c:efifb_remove
  - drivers/video/fbdev/simplefb.c:simplefb_remove
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
**Symbols:**

```
ffffffff815b59f0-ffffffff815b5a1c: framebuffer_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void framebuffer_release(struct fb_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff815cf460)
Location: drivers/video/fbdev/core/fbsysfs.c:79
Inline: True
Direct callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_remove
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/efifb.c:efifb_remove
  - drivers/video/fbdev/simplefb.c:simplefb_remove
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
**Symbols:**

```
ffffffff815cf460-ffffffff815cf48c: framebuffer_release (STB_GLOBAL)
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
