# Function: <code>devm_memremap_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void *devm_memremap_pages(struct device *dev, struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff8118b5e0)
Location: kernel/memremap.c:165
Inline: True
```
**Symbols:**

```
ffffffff8118b5e0-ffffffff8118b744: devm_memremap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *devm_memremap_pages(struct device *dev, struct resource *res, struct percpu_ref *ref, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff8119dd10)
Location: kernel/memremap.c:282
Inline: False
```
**Symbols:**

```
ffffffff8119dd10-ffffffff8119e112: devm_memremap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *devm_memremap_pages(struct device *dev, struct resource *res, struct percpu_ref *ref, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff811ad730)
Location: kernel/memremap.c:288
Inline: False
```
**Symbols:**

```
ffffffff811ad730-ffffffff811adb3e: devm_memremap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *devm_memremap_pages(struct device *dev, struct resource *res, struct percpu_ref *ref, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff811b4c00)
Location: kernel/memremap.c:281
Inline: False
```
**Symbols:**

```
ffffffff811b4c00-ffffffff811b5038: devm_memremap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *devm_memremap_pages(struct device *dev, struct resource *res, struct percpu_ref *ref, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff811c8db0)
Location: kernel/memremap.c:346
Inline: False
```
**Symbols:**

```
ffffffff811c8db0-ffffffff811c9241: devm_memremap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *devm_memremap_pages(struct device *dev, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff811e9730)
Location: kernel/memremap.c:170
Inline: False
```
**Symbols:**

```
ffffffff811e9730-ffffffff811e9b68: devm_memremap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *devm_memremap_pages(struct device *dev, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff811fa2e0)
Location: kernel/memremap.c:144
Inline: False
Direct callers:
  - mm/hmm.c:hmm_devmem_add
```
**Symbols:**

```
ffffffff811fa2e0-ffffffff811fa6d9: devm_memremap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *devm_memremap_pages(struct device *dev, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812c2730)
Location: mm/memremap.c:164
Inline: False
```
**Symbols:**

```
ffffffff812c2730-ffffffff812c2d62: devm_memremap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *devm_memremap_pages(struct device *dev, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812d4bc0)
Location: mm/memremap.c:343
Inline: False
```
**Symbols:**

```
ffffffff812d4bc0-ffffffff812d4c1d: devm_memremap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *devm_memremap_pages(struct device *dev, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff8130a990)
Location: mm/memremap.c:376
Inline: False
```
**Symbols:**

```
ffffffff8130a990-ffffffff8130a9ed: devm_memremap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *devm_memremap_pages(struct device *dev, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff81316800)
Location: mm/memremap.c:425
Inline: False
```
**Symbols:**

```
ffffffff81316800-ffffffff8131685d: devm_memremap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *devm_memremap_pages(struct device *dev, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff8131ca50)
Location: mm/memremap.c:431
Inline: False
```
**Symbols:**

```
ffffffff8131ca50-ffffffff8131caad: devm_memremap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *devm_memremap_pages(struct device *dev, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff81369da0)
Location: mm/memremap.c:428
Inline: False
```
**Symbols:**

```
ffffffff81369da0-ffffffff81369dfd: devm_memremap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *devm_memremap_pages(struct device *dev, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff813e7aa0)
Location: mm/memremap.c:386
Inline: False
```
**Symbols:**

```
ffffffff813e7aa0-ffffffff813e7b05: devm_memremap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *devm_memremap_pages(struct device *dev, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff8146f7a0)
Location: mm/memremap.c:402
Inline: False
Direct callers:
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
```
**Symbols:**

```
ffffffff8146f7a0-ffffffff8146f805: devm_memremap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *devm_memremap_pages(struct device *dev, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff814a3f80)
Location: mm/memremap.c:402
Inline: False
Direct callers:
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
```
**Symbols:**

```
ffffffff814a3f80-ffffffff814a3fee: devm_memremap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *devm_memremap_pages(struct device *dev, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff814d4e30)
Location: mm/memremap.c:403
Inline: False
Direct callers:
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
```
**Symbols:**

```
ffffffff814d4e30-ffffffff814d4e9e: devm_memremap_pages (STB_GLOBAL)
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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *devm_memremap_pages(struct device *dev, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (c00000000046e510)
Location: mm/memremap.c:343
Inline: False
```
**Symbols:**

```
c00000000046e510-c00000000046e5a8: devm_memremap_pages (STB_GLOBAL)
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
void *devm_memremap_pages(struct device *dev, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812cd1a0)
Location: mm/memremap.c:343
Inline: False
```
**Symbols:**

```
ffffffff812cd1a0-ffffffff812cd1fd: devm_memremap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *devm_memremap_pages(struct device *dev, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812be010)
Location: mm/memremap.c:343
Inline: False
Direct callers:
  - drivers/nvdimm/pmem.c:pmem_attach_disk
  - drivers/nvdimm/pmem.c:pmem_attach_disk
  - drivers/dax/device.c:dev_dax_probe
```
**Symbols:**

```
ffffffff812be010-ffffffff812be06d: devm_memremap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *devm_memremap_pages(struct device *dev, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812cafb0)
Location: mm/memremap.c:343
Inline: False
```
**Symbols:**

```
ffffffff812cafb0-ffffffff812cb00d: devm_memremap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *devm_memremap_pages(struct device *dev, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812dbd10)
Location: mm/memremap.c:343
Inline: False
```
**Symbols:**

```
ffffffff812dbd10-ffffffff812dbd6d: devm_memremap_pages (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct percpu_ref *ref</code>
</li>
<li>
<b>Param added. </b>
<code>struct vmem_altmap *altmap</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct dev_pagemap *pgmap</code>
</li>
<li>
<b>Param removed. </b>
<code>struct resource *res</code>
</li>
<li>
<b>Param removed. </b>
<code>struct percpu_ref *ref</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vmem_altmap *altmap</code>
</li>
</ul>
</details>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
