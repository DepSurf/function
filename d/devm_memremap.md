# Function: <code>devm_memremap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *devm_memremap(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff8118b870)
Location: kernel/memremap.c:122
Inline: False
```
**Symbols:**

```
ffffffff8118b870-ffffffff8118b905: devm_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *devm_memremap(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff8119e4e0)
Location: kernel/memremap.c:142
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
**Symbols:**

```
ffffffff8119e4e0-ffffffff8119e583: devm_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *devm_memremap(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff811adf10)
Location: kernel/memremap.c:142
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
**Symbols:**

```
ffffffff811adf10-ffffffff811adfb3: devm_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *devm_memremap(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff811b5390)
Location: kernel/memremap.c:142
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
**Symbols:**

```
ffffffff811b5390-ffffffff811b5433: devm_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *devm_memremap(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff811c8be0)
Location: kernel/memremap.c:155
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
**Symbols:**

```
ffffffff811c8be0-ffffffff811c8c83: devm_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *devm_memremap(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff811e9110)
Location: kernel/iomem.c:139
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
**Symbols:**

```
ffffffff811e9110-ffffffff811e91a7: devm_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *devm_memremap(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff811f9e20)
Location: kernel/iomem.c:139
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
**Symbols:**

```
ffffffff811f9e20-ffffffff811f9eb7: devm_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *devm_memremap(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff81211d90)
Location: kernel/iomem.c:139
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
```
**Symbols:**

```
ffffffff81211d90-ffffffff81211e2b: devm_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *devm_memremap(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff8121f580)
Location: kernel/iomem.c:139
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
```
**Symbols:**

```
ffffffff8121f580-ffffffff8121f61b: devm_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *devm_memremap(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff8124b820)
Location: kernel/iomem.c:139
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
```
**Symbols:**

```
ffffffff8124b820-ffffffff8124b8bb: devm_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *devm_memremap(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff81255c10)
Location: kernel/iomem.c:139
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
```
**Symbols:**

```
ffffffff81255c10-ffffffff81255cab: devm_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *devm_memremap(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff8125a1d0)
Location: kernel/iomem.c:139
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
```
**Symbols:**

```
ffffffff8125a1d0-ffffffff8125a26b: devm_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *devm_memremap(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff81295fe0)
Location: kernel/iomem.c:139
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
```
**Symbols:**

```
ffffffff81295fe0-ffffffff81296082: devm_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *devm_memremap(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff812ebd90)
Location: kernel/iomem.c:139
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
```
**Symbols:**

```
ffffffff812ebd90-ffffffff812ebe50: devm_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *devm_memremap(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff81355f60)
Location: kernel/iomem.c:139
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
```
**Symbols:**

```
ffffffff81355f60-ffffffff81356020: devm_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *devm_memremap(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff813875e0)
Location: kernel/iomem.c:139
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
```
**Symbols:**

```
ffffffff813875e0-ffffffff813876a0: devm_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *devm_memremap(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff813b10a0)
Location: kernel/iomem.c:136
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
```
**Symbols:**

```
ffffffff813b10a0-ffffffff813b1160: devm_memremap (STB_GLOBAL)
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
void *devm_memremap(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffff8000102abd90)
Location: kernel/iomem.c:139
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
```
**Symbols:**

```
ffff8000102abd90-ffff8000102abe48: devm_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *devm_memremap(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (c04d8fdc)
Location: kernel/iomem.c:139
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
```
**Symbols:**

```
c04d8fdc-c04d906c: devm_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *devm_memremap(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (c00000000035fd50)
Location: kernel/iomem.c:139
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
```
**Symbols:**

```
c00000000035fd50-c00000000035fe50: devm_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *devm_memremap(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffe0001d3750)
Location: kernel/iomem.c:139
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
```
**Symbols:**

```
ffffffe0001d3750-ffffffe0001d37da: devm_memremap (STB_GLOBAL)
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
void *devm_memremap(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff81217bd0)
Location: kernel/iomem.c:139
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
```
**Symbols:**

```
ffffffff81217bd0-ffffffff81217c6b: devm_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *devm_memremap(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff8120ade0)
Location: kernel/iomem.c:139
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/nvdimm/pmem.c:pmem_attach_disk
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
```
**Symbols:**

```
ffffffff8120ade0-ffffffff8120ae7b: devm_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *devm_memremap(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff81215970)
Location: kernel/iomem.c:139
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
```
**Symbols:**

```
ffffffff81215970-ffffffff81215a0b: devm_memremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *devm_memremap(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff81224970)
Location: kernel/iomem.c:139
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
```
**Symbols:**

```
ffffffff81224970-ffffffff81224a0b: devm_memremap (STB_GLOBAL)
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
