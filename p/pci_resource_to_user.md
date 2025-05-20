# Function: <code>pci_resource_to_user</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_mmiotrace.c (ffffffff81158af7)
Location: include/linux/pci.h:1564
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
```
```
In drivers/pci/pci-sysfs.c (0)
Location: include/linux/pci.h:1564
Inline: True
```
```
In drivers/pci/proc.c (ffffffff814418fb)
Location: include/linux/pci.h:1564
Inline: True
Inline callers:
  - drivers/pci/proc.c:show_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (0)
Location: include/linux/pci.h:1626
Inline: True
```
```
In drivers/pci/proc.c (ffffffff8148d806)
Location: include/linux/pci.h:1626
Inline: True
Inline callers:
  - drivers/pci/proc.c:show_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (0)
Location: include/linux/pci.h:1688
Inline: True
```
```
In drivers/pci/proc.c (ffffffff814aeff6)
Location: include/linux/pci.h:1688
Inline: True
Inline callers:
  - drivers/pci/proc.c:show_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (0)
Location: include/linux/pci.h:1720
Inline: True
```
```
In drivers/pci/mmap.c (0)
Location: include/linux/pci.h:1720
Inline: True
```
```
In drivers/pci/proc.c (ffffffff814b9955)
Location: include/linux/pci.h:1720
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (0)
Location: include/linux/pci.h:1776
Inline: True
```
```
In drivers/pci/mmap.c (0)
Location: include/linux/pci.h:1776
Inline: True
```
```
In drivers/pci/proc.c (ffffffff814f9d25)
Location: include/linux/pci.h:1776
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff81522d02)
Location: include/linux/pci.h:1777
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:resource_show
```
```
In drivers/pci/mmap.c (0)
Location: include/linux/pci.h:1777
Inline: True
```
```
In drivers/pci/proc.c (ffffffff8152a7fc)
Location: include/linux/pci.h:1777
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff81538b42)
Location: include/linux/pci.h:1811
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:resource_show
```
```
In drivers/pci/mmap.c (0)
Location: include/linux/pci.h:1811
Inline: True
```
```
In drivers/pci/proc.c (ffffffff8154067c)
Location: include/linux/pci.h:1811
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff81568529)
Location: include/linux/pci.h:1885
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:resource_show
```
```
In drivers/pci/mmap.c (0)
Location: include/linux/pci.h:1885
Inline: True
```
```
In drivers/pci/proc.c (ffffffff8156ff77)
Location: include/linux/pci.h:1885
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pci_resource_to_user(const struct pci_dev *dev, int bar, const struct resource *rsrc, resource_size_t *start, resource_size_t *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81585980)
Location: drivers/pci/pci.c:6090
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_mmap_fits
  - drivers/pci/pci-sysfs.c:resource_show
  - drivers/pci/mmap.c:pci_mmap_page_range
```
**Symbols:**

```
ffffffff81585980-ffffffff81585998: pci_resource_to_user (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pci_resource_to_user(const struct pci_dev *dev, int bar, const struct resource *rsrc, resource_size_t *start, resource_size_t *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162c730)
Location: drivers/pci/pci.c:6128
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_mmap_fits
  - drivers/pci/pci-sysfs.c:resource_show
  - drivers/pci/mmap.c:pci_mmap_page_range
```
**Symbols:**

```
ffffffff8162c730-ffffffff8162c748: pci_resource_to_user (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pci_resource_to_user(const struct pci_dev *dev, int bar, const struct resource *rsrc, resource_size_t *start, resource_size_t *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816524a0)
Location: drivers/pci/pci.c:6202
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_mmap_fits
  - drivers/pci/pci-sysfs.c:resource_show
  - drivers/pci/mmap.c:pci_mmap_page_range
```
**Symbols:**

```
ffffffff816524a0-ffffffff816524b8: pci_resource_to_user (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pci_resource_to_user(const struct pci_dev *dev, int bar, const struct resource *rsrc, resource_size_t *start, resource_size_t *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81634f60)
Location: drivers/pci/pci.c:6251
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_mmap_fits
  - drivers/pci/pci-sysfs.c:resource_show
  - drivers/pci/mmap.c:pci_mmap_page_range
```
**Symbols:**

```
ffffffff81634f60-ffffffff81634f78: pci_resource_to_user (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pci_resource_to_user(const struct pci_dev *dev, int bar, const struct resource *rsrc, resource_size_t *start, resource_size_t *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816a5060)
Location: drivers/pci/pci.c:6441
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_mmap_fits
  - drivers/pci/pci-sysfs.c:resource_show
  - drivers/pci/mmap.c:pci_mmap_page_range
```
**Symbols:**

```
ffffffff816a5060-ffffffff816a5078: pci_resource_to_user (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pci_resource_to_user(const struct pci_dev *dev, int bar, const struct resource *rsrc, resource_size_t *start, resource_size_t *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c75b0)
Location: drivers/pci/pci.c:6538
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_mmap_fits
  - drivers/pci/pci-sysfs.c:resource_show
  - drivers/pci/mmap.c:pci_mmap_page_range
```
**Symbols:**

```
ffffffff817c75b0-ffffffff817c75d5: pci_resource_to_user (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_resource_to_user(const struct pci_dev *dev, int bar, const struct resource *rsrc, resource_size_t *start, resource_size_t *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818e4be0)
Location: drivers/pci/pci.c:6487
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_mmap_fits
  - drivers/pci/pci-sysfs.c:resource_show
  - drivers/pci/proc.c:proc_bus_pci_mmap
```
**Symbols:**

```
ffffffff818e4be0-ffffffff818e4c05: pci_resource_to_user (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pci_resource_to_user(const struct pci_dev *dev, int bar, const struct resource *rsrc, resource_size_t *start, resource_size_t *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81928220)
Location: drivers/pci/pci.c:6609
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_mmap_fits
  - drivers/pci/pci-sysfs.c:resource_show
  - drivers/pci/proc.c:proc_bus_pci_mmap
```
**Symbols:**

```
ffffffff81928220-ffffffff81928245: pci_resource_to_user (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_resource_to_user(const struct pci_dev *dev, int bar, const struct resource *rsrc, resource_size_t *start, resource_size_t *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff819709c0)
Location: drivers/pci/pci.c:6753
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_mmap_fits
  - drivers/pci/pci-sysfs.c:resource_show
  - drivers/pci/proc.c:proc_bus_pci_mmap
```
**Symbols:**

```
ffffffff819709c0-ffffffff819709e5: pci_resource_to_user (STB_WEAK)
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
void pci_resource_to_user(const struct pci_dev *dev, int bar, const struct resource *rsrc, resource_size_t *start, resource_size_t *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106ea398)
Location: drivers/pci/pci.c:6090
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_mmap_fits
  - drivers/pci/pci-sysfs.c:resource_show
```
**Symbols:**

```
ffff8000106ea398-ffff8000106ea3dc: pci_resource_to_user (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pci_resource_to_user(const struct pci_dev *dev, int bar, const struct resource *rsrc, resource_size_t *start, resource_size_t *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c0885334)
Location: drivers/pci/pci.c:6090
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_mmap_fits
  - drivers/pci/pci-sysfs.c:resource_show
  - drivers/pci/mmap.c:pci_mmap_page_range
```
**Symbols:**

```
c0885334-c0885360: pci_resource_to_user (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pci_resource_to_user(const struct pci_dev *dev, int bar, const struct resource *rsrc, resource_size_t *start, resource_size_t *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/pci-common.c (c00000000006dd20)
Location: arch/powerpc/kernel/pci-common.c:620
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_mmap_fits
  - drivers/pci/pci-sysfs.c:resource_show
  - drivers/pci/mmap.c:pci_mmap_page_range
```
**Symbols:**

```
c00000000006dd20-c00000000006ddd4: pci_resource_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pci_resource_to_user(const struct pci_dev *dev, int bar, const struct resource *rsrc, resource_size_t *start, resource_size_t *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004c050a)
Location: drivers/pci/pci.c:6090
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:resource_show
```
**Symbols:**

```
ffffffe0004c050a-ffffffe0004c0542: pci_resource_to_user (STB_WEAK)
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
void pci_resource_to_user(const struct pci_dev *dev, int bar, const struct resource *rsrc, resource_size_t *start, resource_size_t *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81579ea0)
Location: drivers/pci/pci.c:6090
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_mmap_fits
  - drivers/pci/pci-sysfs.c:resource_show
  - drivers/pci/mmap.c:pci_mmap_page_range
```
**Symbols:**

```
ffffffff81579ea0-ffffffff81579eb8: pci_resource_to_user (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pci_resource_to_user(const struct pci_dev *dev, int bar, const struct resource *rsrc, resource_size_t *start, resource_size_t *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815685e0)
Location: drivers/pci/pci.c:6090
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_mmap_fits
  - drivers/pci/pci-sysfs.c:resource_show
  - drivers/pci/mmap.c:pci_mmap_page_range
```
**Symbols:**

```
ffffffff815685e0-ffffffff815685f8: pci_resource_to_user (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pci_resource_to_user(const struct pci_dev *dev, int bar, const struct resource *rsrc, resource_size_t *start, resource_size_t *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815796d0)
Location: drivers/pci/pci.c:6090
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_mmap_fits
  - drivers/pci/pci-sysfs.c:resource_show
  - drivers/pci/mmap.c:pci_mmap_page_range
```
**Symbols:**

```
ffffffff815796d0-ffffffff815796e8: pci_resource_to_user (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pci_resource_to_user(const struct pci_dev *dev, int bar, const struct resource *rsrc, resource_size_t *start, resource_size_t *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81593b60)
Location: drivers/pci/pci.c:6090
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_mmap_fits
  - drivers/pci/pci-sysfs.c:resource_show
  - drivers/pci/mmap.c:pci_mmap_page_range
```
**Symbols:**

```
ffffffff81593b60-ffffffff81593b78: pci_resource_to_user (STB_WEAK)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
