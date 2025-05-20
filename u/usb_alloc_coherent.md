# Function: <code>usb_alloc_coherent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *usb_alloc_coherent(struct usb_device *dev, size_t size, gfp_t mem_flags, dma_addr_t *dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81603480)
Location: drivers/usb/core/usb.c:730
Inline: False
```
**Symbols:**

```
ffffffff81603480-ffffffff816034a1: usb_alloc_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *usb_alloc_coherent(struct usb_device *dev, size_t size, gfp_t mem_flags, dma_addr_t *dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81663140)
Location: drivers/usb/core/usb.c:735
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
**Symbols:**

```
ffffffff81663140-ffffffff81663161: usb_alloc_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *usb_alloc_coherent(struct usb_device *dev, size_t size, gfp_t mem_flags, dma_addr_t *dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81690f30)
Location: drivers/usb/core/usb.c:749
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
**Symbols:**

```
ffffffff81690f30-ffffffff81690f51: usb_alloc_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *usb_alloc_coherent(struct usb_device *dev, size_t size, gfp_t mem_flags, dma_addr_t *dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff816a64c0)
Location: drivers/usb/core/usb.c:885
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
**Symbols:**

```
ffffffff816a64c0-ffffffff816a64e1: usb_alloc_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *usb_alloc_coherent(struct usb_device *dev, size_t size, gfp_t mem_flags, dma_addr_t *dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81711890)
Location: drivers/usb/core/usb.c:885
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
**Symbols:**

```
ffffffff81711890-ffffffff817118b1: usb_alloc_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *usb_alloc_coherent(struct usb_device *dev, size_t size, gfp_t mem_flags, dma_addr_t *dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff817505c0)
Location: drivers/usb/core/usb.c:886
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
**Symbols:**

```
ffffffff817505c0-ffffffff817505e1: usb_alloc_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *usb_alloc_coherent(struct usb_device *dev, size_t size, gfp_t mem_flags, dma_addr_t *dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81774a00)
Location: drivers/usb/core/usb.c:886
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
**Symbols:**

```
ffffffff81774a00-ffffffff81774a25: usb_alloc_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *usb_alloc_coherent(struct usb_device *dev, size_t size, gfp_t mem_flags, dma_addr_t *dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff817b2b20)
Location: drivers/usb/core/usb.c:905
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
**Symbols:**

```
ffffffff817b2b20-ffffffff817b2b45: usb_alloc_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *usb_alloc_coherent(struct usb_device *dev, size_t size, gfp_t mem_flags, dma_addr_t *dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff817e3250)
Location: drivers/usb/core/usb.c:905
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
**Symbols:**

```
ffffffff817e3250-ffffffff817e3275: usb_alloc_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *usb_alloc_coherent(struct usb_device *dev, size_t size, gfp_t mem_flags, dma_addr_t *dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff818b1da0)
Location: drivers/usb/core/usb.c:905
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
**Symbols:**

```
ffffffff818b1da0-ffffffff818b1dc5: usb_alloc_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *usb_alloc_coherent(struct usb_device *dev, size_t size, gfp_t mem_flags, dma_addr_t *dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff818c0790)
Location: drivers/usb/core/usb.c:924
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
**Symbols:**

```
ffffffff818c0790-ffffffff818c07b5: usb_alloc_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *usb_alloc_coherent(struct usb_device *dev, size_t size, gfp_t mem_flags, dma_addr_t *dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff818a3a10)
Location: drivers/usb/core/usb.c:970
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
**Symbols:**

```
ffffffff818a3a10-ffffffff818a3a35: usb_alloc_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *usb_alloc_coherent(struct usb_device *dev, size_t size, gfp_t mem_flags, dma_addr_t *dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff819385d0)
Location: drivers/usb/core/usb.c:970
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
**Symbols:**

```
ffffffff819385d0-ffffffff819385f5: usb_alloc_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *usb_alloc_coherent(struct usb_device *dev, size_t size, gfp_t mem_flags, dma_addr_t *dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81a8ff00)
Location: drivers/usb/core/usb.c:932
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
**Symbols:**

```
ffffffff81a8ff00-ffffffff81a8ff49: usb_alloc_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *usb_alloc_coherent(struct usb_device *dev, size_t size, gfp_t mem_flags, dma_addr_t *dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81c11da0)
Location: drivers/usb/core/usb.c:932
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
**Symbols:**

```
ffffffff81c11da0-ffffffff81c11de9: usb_alloc_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *usb_alloc_coherent(struct usb_device *dev, size_t size, gfp_t mem_flags, dma_addr_t *dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81c78b60)
Location: drivers/usb/core/usb.c:1008
Inline: False
```
**Symbols:**

```
ffffffff81c78b60-ffffffff81c78ba9: usb_alloc_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *usb_alloc_coherent(struct usb_device *dev, size_t size, gfp_t mem_flags, dma_addr_t *dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81d2d560)
Location: drivers/usb/core/usb.c:996
Inline: False
```
**Symbols:**

```
ffffffff81d2d560-ffffffff81d2d5a9: usb_alloc_coherent (STB_GLOBAL)
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
void *usb_alloc_coherent(struct usb_device *dev, size_t size, gfp_t mem_flags, dma_addr_t *dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffff800010a117c0)
Location: drivers/usb/core/usb.c:905
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
**Symbols:**

```
ffff800010a117c0-ffff800010a1181c: usb_alloc_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *usb_alloc_coherent(struct usb_device *dev, size_t size, gfp_t mem_flags, dma_addr_t *dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (c0aea024)
Location: drivers/usb/core/usb.c:905
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
**Symbols:**

```
c0aea024-c0aea054: usb_alloc_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *usb_alloc_coherent(struct usb_device *dev, size_t size, gfp_t mem_flags, dma_addr_t *dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (c000000000ac8950)
Location: drivers/usb/core/usb.c:905
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
**Symbols:**

```
c000000000ac8950-c000000000ac89a8: usb_alloc_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *usb_alloc_coherent(struct usb_device *dev, size_t size, gfp_t mem_flags, dma_addr_t *dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffe00063727a)
Location: drivers/usb/core/usb.c:905
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
**Symbols:**

```
ffffffe00063727a-ffffffe0006372c4: usb_alloc_coherent (STB_GLOBAL)
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
void *usb_alloc_coherent(struct usb_device *dev, size_t size, gfp_t mem_flags, dma_addr_t *dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff8179b630)
Location: drivers/usb/core/usb.c:905
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
**Symbols:**

```
ffffffff8179b630-ffffffff8179b655: usb_alloc_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *usb_alloc_coherent(struct usb_device *dev, size_t size, gfp_t mem_flags, dma_addr_t *dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff8178d2c0)
Location: drivers/usb/core/usb.c:905
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
**Symbols:**

```
ffffffff8178d2c0-ffffffff8178d2e5: usb_alloc_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *usb_alloc_coherent(struct usb_device *dev, size_t size, gfp_t mem_flags, dma_addr_t *dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff817d80d0)
Location: drivers/usb/core/usb.c:905
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
**Symbols:**

```
ffffffff817d80d0-ffffffff817d80f5: usb_alloc_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *usb_alloc_coherent(struct usb_device *dev, size_t size, gfp_t mem_flags, dma_addr_t *dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff817f2370)
Location: drivers/usb/core/usb.c:905
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
**Symbols:**

```
ffffffff817f2370-ffffffff817f2395: usb_alloc_coherent (STB_GLOBAL)
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
