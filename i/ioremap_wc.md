# Function: <code>ioremap_wc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *ioremap_wc(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff8106bd20)
Location: arch/x86/mm/ioremap.c:289
Inline: False
Direct callers:
  - lib/pci_iomap.c:pci_iomap_wc_range
  - lib/devres.c:devm_ioremap_wc
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
**Symbols:**

```
ffffffff8106bd20-ffffffff8106bd39: ioremap_wc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *ioremap_wc(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff8106bbd0)
Location: arch/x86/mm/ioremap.c:288
Inline: False
Direct callers:
  - kernel/memremap.c:memremap
  - lib/pci_iomap.c:pci_iomap_wc_range
  - lib/devres.c:devm_ioremap_wc
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
**Symbols:**

```
ffffffff8106bbd0-ffffffff8106bbe9: ioremap_wc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *ioremap_wc(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff8106f7f0)
Location: arch/x86/mm/ioremap.c:288
Inline: False
Direct callers:
  - kernel/memremap.c:memremap
  - lib/pci_iomap.c:pci_iomap_wc_range
  - lib/devres.c:devm_ioremap_wc
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
**Symbols:**

```
ffffffff8106f7f0-ffffffff8106f809: ioremap_wc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *ioremap_wc(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff8106ef20)
Location: arch/x86/mm/ioremap.c:289
Inline: False
Direct callers:
  - kernel/memremap.c:memremap
  - lib/pci_iomap.c:pci_iomap_wc_range
  - lib/devres.c:devm_ioremap_wc
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
**Symbols:**

```
ffffffff8106ef20-ffffffff8106ef39: ioremap_wc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *ioremap_wc(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81074010)
Location: arch/x86/mm/ioremap.c:341
Inline: False
Direct callers:
  - kernel/memremap.c:memremap
  - lib/pci_iomap.c:pci_iomap_wc_range
  - lib/devres.c:devm_ioremap_wc
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
**Symbols:**

```
ffffffff81074010-ffffffff81074029: ioremap_wc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *ioremap_wc(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81076a20)
Location: arch/x86/mm/ioremap.c:341
Inline: False
Direct callers:
  - kernel/iomem.c:memremap
  - lib/pci_iomap.c:pci_iomap_wc_range
  - lib/devres.c:__devm_ioremap
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
**Symbols:**

```
ffffffff81076a20-ffffffff81076a39: ioremap_wc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *ioremap_wc(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff8107d090)
Location: arch/x86/mm/ioremap.c:342
Inline: False
Direct callers:
  - kernel/iomem.c:memremap
  - lib/pci_iomap.c:pci_iomap_wc_range
  - lib/devres.c:__devm_ioremap
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
**Symbols:**

```
ffffffff8107d090-ffffffff8107d0ac: ioremap_wc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *ioremap_wc(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810807e0)
Location: arch/x86/mm/ioremap.c:362
Inline: False
Direct callers:
  - kernel/iomem.c:memremap
  - lib/pci_iomap.c:pci_iomap_wc_range
  - lib/devres.c:__devm_ioremap
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
**Symbols:**

```
ffffffff810807e0-ffffffff810807fc: ioremap_wc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *ioremap_wc(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810819e0)
Location: arch/x86/mm/ioremap.c:384
Inline: False
Direct callers:
  - kernel/iomem.c:memremap
  - lib/pci_iomap.c:pci_iomap_wc_range
  - lib/devres.c:__devm_ioremap
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
**Symbols:**

```
ffffffff810819e0-ffffffff810819fc: ioremap_wc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *ioremap_wc(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81088990)
Location: arch/x86/mm/ioremap.c:384
Inline: False
Direct callers:
  - kernel/iomem.c:memremap
  - lib/pci_iomap.c:pci_iomap_wc
  - lib/devres.c:devm_ioremap_wc
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
**Symbols:**

```
ffffffff81088990-ffffffff810889ac: ioremap_wc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *ioremap_wc(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81088bd0)
Location: arch/x86/mm/ioremap.c:384
Inline: False
Direct callers:
  - kernel/iomem.c:memremap
  - lib/pci_iomap.c:pci_iomap_wc
  - lib/devres.c:devm_ioremap_wc
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
**Symbols:**

```
ffffffff81088bd0-ffffffff81088bec: ioremap_wc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *ioremap_wc(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81089870)
Location: arch/x86/mm/ioremap.c:386
Inline: False
Direct callers:
  - kernel/iomem.c:memremap
  - lib/pci_iomap.c:pci_iomap_wc
  - lib/devres.c:devm_ioremap_wc
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
**Symbols:**

```
ffffffff81089870-ffffffff8108988c: ioremap_wc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *ioremap_wc(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81098d10)
Location: arch/x86/mm/ioremap.c:386
Inline: False
Direct callers:
  - kernel/iomem.c:memremap
  - lib/pci_iomap.c:pci_iomap_wc
  - lib/devres.c:devm_ioremap_wc
  - drivers/pci/pci.c:pci_ioremap_wc_bar
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
**Symbols:**

```
ffffffff81098d10-ffffffff81098d2c: ioremap_wc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *ioremap_wc(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810abaf0)
Location: arch/x86/mm/ioremap.c:391
Inline: False
Direct callers:
  - kernel/iomem.c:memremap
  - lib/pci_iomap.c:pci_iomap_wc
  - lib/devres.c:devm_ioremap_wc
  - drivers/pci/pci.c:pci_ioremap_wc_bar
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
**Symbols:**

```
ffffffff810abaf0-ffffffff810abb1b: ioremap_wc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *ioremap_wc(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810c5510)
Location: arch/x86/mm/ioremap.c:398
Inline: False
Direct callers:
  - kernel/iomem.c:memremap
  - lib/pci_iomap.c:pci_iomap_wc
  - lib/devres.c:devm_ioremap_wc
  - drivers/pci/pci.c:pci_ioremap_wc_bar
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
**Symbols:**

```
ffffffff810c5510-ffffffff810c553b: ioremap_wc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *ioremap_wc(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810c8ca0)
Location: arch/x86/mm/ioremap.c:403
Inline: False
Direct callers:
  - kernel/iomem.c:memremap
  - lib/pci_iomap.c:pci_iomap_wc
  - lib/devres.c:devm_ioremap_wc
  - drivers/pci/pci.c:pci_ioremap_wc_bar
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
**Symbols:**

```
ffffffff810c8ca0-ffffffff810c8ccb: ioremap_wc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *ioremap_wc(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810d13a0)
Location: arch/x86/mm/ioremap.c:403
Inline: False
Direct callers:
  - kernel/iomem.c:memremap
  - lib/pci_iomap.c:pci_iomap_wc
  - lib/devres.c:devm_ioremap_wc
  - drivers/pci/pci.c:pci_ioremap_wc_bar
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
**Symbols:**

```
ffffffff810d13a0-ffffffff810d13cb: ioremap_wc (STB_GLOBAL)
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
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *ioremap_wc(resource_size_t res_cookie, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/mm/ioremap.c (c031f26c)
Location: arch/arm/mm/ioremap.c:395
Inline: False
Direct callers:
  - kernel/iomem.c:memremap
  - kernel/iomem.c:memremap
  - fs/pstore/ram_core.c:persistent_ram_new
  - lib/pci_iomap.c:pci_iomap_wc_range
  - lib/devres.c:__devm_ioremap
  - drivers/video/fbdev/omap2/omapfb/vrfb.c:omap_vrfb_map_angle
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
**Symbols:**

```
c031f26c-c031f29c: ioremap_wc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *ioremap_wc(phys_addr_t addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/ioremap.c (c000000000089460)
Location: arch/powerpc/mm/ioremap.c:22
Inline: False
Direct callers:
  - kernel/iomem.c:memremap
  - lib/pci_iomap.c:pci_iomap_wc_range
  - lib/devres.c:__devm_ioremap
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
**Symbols:**

```
c000000000089460-c0000000000894a4: ioremap_wc (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void *ioremap_wc(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810809e0)
Location: arch/x86/mm/ioremap.c:384
Inline: False
Direct callers:
  - kernel/iomem.c:memremap
  - lib/pci_iomap.c:pci_iomap_wc_range
  - lib/devres.c:__devm_ioremap
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
**Symbols:**

```
ffffffff810809e0-ffffffff810809fc: ioremap_wc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *ioremap_wc(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff8106f930)
Location: arch/x86/mm/ioremap.c:384
Inline: False
Direct callers:
  - kernel/iomem.c:memremap
  - lib/pci_iomap.c:pci_iomap_wc_range
  - lib/devres.c:__devm_ioremap
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
**Symbols:**

```
ffffffff8106f930-ffffffff8106f94c: ioremap_wc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *ioremap_wc(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81080990)
Location: arch/x86/mm/ioremap.c:384
Inline: False
Direct callers:
  - kernel/iomem.c:memremap
  - lib/pci_iomap.c:pci_iomap_wc_range
  - lib/devres.c:__devm_ioremap
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
**Symbols:**

```
ffffffff81080990-ffffffff810809ac: ioremap_wc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *ioremap_wc(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81082ab0)
Location: arch/x86/mm/ioremap.c:384
Inline: False
Direct callers:
  - kernel/iomem.c:memremap
  - lib/pci_iomap.c:pci_iomap_wc_range
  - lib/devres.c:__devm_ioremap
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
**Symbols:**

```
ffffffff81082ab0-ffffffff81082acc: ioremap_wc (STB_GLOBAL)
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
<details>
<summary>Changed between <code>amd64</code> and <code>armhf</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>resource_size_t res_cookie</code>
</li>
<li>
<b>Param removed. </b>
<code>resource_size_t phys_addr</code>
</li>
<li>
<b>Param type changed. </b>
<code>long unsigned int size</code> ➡️ <code>size_t size</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>phys_addr_t addr</code>
</li>
<li>
<b>Param removed. </b>
<code>resource_size_t phys_addr</code>
</li>
</ul>
</details>
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
