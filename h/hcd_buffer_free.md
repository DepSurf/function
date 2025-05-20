# Function: <code>hcd_buffer_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void hcd_buffer_free(struct usb_bus *bus, size_t size, void *addr, dma_addr_t dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/buffer.c (ffffffff81617a10)
Location: drivers/usb/core/buffer.c:135
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_free_coherent
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
```
**Symbols:**

```
ffffffff81617a10-ffffffff81617b29: hcd_buffer_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void hcd_buffer_free(struct usb_bus *bus, size_t size, void *addr, dma_addr_t dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/buffer.c (ffffffff81677ae0)
Location: drivers/usb/core/buffer.c:143
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_free_coherent
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
**Symbols:**

```
ffffffff81677ae0-ffffffff81677bf9: hcd_buffer_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void hcd_buffer_free(struct usb_bus *bus, size_t size, void *addr, dma_addr_t dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/buffer.c (ffffffff816a57c0)
Location: drivers/usb/core/buffer.c:146
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_free_coherent
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
**Symbols:**

```
ffffffff816a57c0-ffffffff816a58d9: hcd_buffer_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void hcd_buffer_free(struct usb_bus *bus, size_t size, void *addr, dma_addr_t dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/buffer.c (ffffffff816bab50)
Location: drivers/usb/core/buffer.c:146
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_free_coherent
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
**Symbols:**

```
ffffffff816bab50-ffffffff816bac32: hcd_buffer_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void hcd_buffer_free(struct usb_bus *bus, size_t size, void *addr, dma_addr_t dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/buffer.c (ffffffff81726510)
Location: drivers/usb/core/buffer.c:146
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_free_coherent
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
**Symbols:**

```
ffffffff81726510-ffffffff817265f5: hcd_buffer_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void hcd_buffer_free(struct usb_bus *bus, size_t size, void *addr, dma_addr_t dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/buffer.c (ffffffff81765310)
Location: drivers/usb/core/buffer.c:146
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_free_coherent
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
**Symbols:**

```
ffffffff81765310-ffffffff817653f8: hcd_buffer_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void hcd_buffer_free(struct usb_bus *bus, size_t size, void *addr, dma_addr_t dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/buffer.c (ffffffff817898d0)
Location: drivers/usb/core/buffer.c:142
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_free_coherent
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
**Symbols:**

```
ffffffff817898d0-ffffffff8178996c: hcd_buffer_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void hcd_buffer_free(struct usb_bus *bus, size_t size, void *addr, dma_addr_t dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/buffer.c (ffffffff817c7d10)
Location: drivers/usb/core/buffer.c:142
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_free_coherent
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
**Symbols:**

```
ffffffff817c7d10-ffffffff817c7d8f: hcd_buffer_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void hcd_buffer_free(struct usb_bus *bus, size_t size, void *addr, dma_addr_t dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/buffer.c (ffffffff817f8840)
Location: drivers/usb/core/buffer.c:142
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_free_coherent
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
**Symbols:**

```
ffffffff817f8840-ffffffff817f88c6: hcd_buffer_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void hcd_buffer_free(struct usb_bus *bus, size_t size, void *addr, dma_addr_t dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/buffer.c (ffffffff818c89a0)
Location: drivers/usb/core/buffer.c:142
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_free_coherent
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
**Symbols:**

```
ffffffff818c89a0-ffffffff818c8a42: hcd_buffer_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void hcd_buffer_free(struct usb_bus *bus, size_t size, void *addr, dma_addr_t dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/buffer.c (ffffffff818d3af0)
Location: drivers/usb/core/buffer.c:144
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_free_coherent
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
**Symbols:**

```
ffffffff818d3af0-ffffffff818d3b92: hcd_buffer_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void hcd_buffer_free(struct usb_bus *bus, size_t size, void *addr, dma_addr_t dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/buffer.c (ffffffff818b7050)
Location: drivers/usb/core/buffer.c:144
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_free_coherent
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
**Symbols:**

```
ffffffff818b7050-ffffffff818b70f2: hcd_buffer_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void hcd_buffer_free(struct usb_bus *bus, size_t size, void *addr, dma_addr_t dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/buffer.c (ffffffff8194cb30)
Location: drivers/usb/core/buffer.c:144
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_free_coherent
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
**Symbols:**

```
ffffffff8194cb30-ffffffff8194cbd2: hcd_buffer_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void hcd_buffer_free(struct usb_bus *bus, size_t size, void *addr, dma_addr_t dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/buffer.c (ffffffff81aa5700)
Location: drivers/usb/core/buffer.c:144
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_free_coherent
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
**Symbols:**

```
ffffffff81aa5700-ffffffff81aa580e: hcd_buffer_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void hcd_buffer_free(struct usb_bus *bus, size_t size, void *addr, dma_addr_t dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/buffer.c (ffffffff81c2c170)
Location: drivers/usb/core/buffer.c:144
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_free_coherent
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
**Symbols:**

```
ffffffff81c2c170-ffffffff81c2c27e: hcd_buffer_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void hcd_buffer_free(struct usb_bus *bus, size_t size, void *addr, dma_addr_t dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/buffer.c (ffffffff81c93100)
Location: drivers/usb/core/buffer.c:144
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_free_coherent
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
**Symbols:**

```
ffffffff81c93100-ffffffff81c9320e: hcd_buffer_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void hcd_buffer_free(struct usb_bus *bus, size_t size, void *addr, dma_addr_t dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/buffer.c (ffffffff81d47bb0)
Location: drivers/usb/core/buffer.c:144
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_free_coherent
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
**Symbols:**

```
ffffffff81d47bb0-ffffffff81d47cbe: hcd_buffer_free (STB_GLOBAL)
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
void hcd_buffer_free(struct usb_bus *bus, size_t size, void *addr, dma_addr_t dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/buffer.c (ffff800010a295c8)
Location: drivers/usb/core/buffer.c:142
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_free_coherent
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
**Symbols:**

```
ffff800010a295c8-ffff800010a296a8: hcd_buffer_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void hcd_buffer_free(struct usb_bus *bus, size_t size, void *addr, dma_addr_t dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/buffer.c (c0aff534)
Location: drivers/usb/core/buffer.c:142
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_free_coherent
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
**Symbols:**

```
c0aff534-c0aff5f0: hcd_buffer_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void hcd_buffer_free(struct usb_bus *bus, size_t size, void *addr, dma_addr_t dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/buffer.c (c000000000ae5b20)
Location: drivers/usb/core/buffer.c:142
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_free_coherent
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
**Symbols:**

```
c000000000ae5b20-c000000000ae5c20: hcd_buffer_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void hcd_buffer_free(struct usb_bus *bus, size_t size, void *addr, dma_addr_t dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/buffer.c (ffffffe00064afe6)
Location: drivers/usb/core/buffer.c:142
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_free_coherent
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
**Symbols:**

```
ffffffe00064afe6-ffffffe00064b0c2: hcd_buffer_free (STB_GLOBAL)
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
void hcd_buffer_free(struct usb_bus *bus, size_t size, void *addr, dma_addr_t dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/buffer.c (ffffffff817b0c20)
Location: drivers/usb/core/buffer.c:142
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_free_coherent
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
**Symbols:**

```
ffffffff817b0c20-ffffffff817b0ca6: hcd_buffer_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void hcd_buffer_free(struct usb_bus *bus, size_t size, void *addr, dma_addr_t dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/buffer.c (ffffffff817a2650)
Location: drivers/usb/core/buffer.c:142
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_free_coherent
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
**Symbols:**

```
ffffffff817a2650-ffffffff817a26d6: hcd_buffer_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void hcd_buffer_free(struct usb_bus *bus, size_t size, void *addr, dma_addr_t dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/buffer.c (ffffffff817ed6c0)
Location: drivers/usb/core/buffer.c:142
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_free_coherent
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
**Symbols:**

```
ffffffff817ed6c0-ffffffff817ed746: hcd_buffer_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void hcd_buffer_free(struct usb_bus *bus, size_t size, void *addr, dma_addr_t dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/buffer.c (ffffffff81807900)
Location: drivers/usb/core/buffer.c:142
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_free_coherent
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
**Symbols:**

```
ffffffff81807900-ffffffff81807986: hcd_buffer_free (STB_GLOBAL)
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
