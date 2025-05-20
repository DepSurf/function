# Function: <code>hcd_alloc_coherent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int hcd_alloc_coherent(struct usb_bus *bus, gfp_t mem_flags, dma_addr_t *dma_handle, void **vaddr_handle, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8160cad0)
Location: drivers/usb/core/hcd.c:1386
Inline: True
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
**Symbols:**

```
ffffffff8160cad0-ffffffff8160cb6e: hcd_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int hcd_alloc_coherent(struct usb_bus *bus, gfp_t mem_flags, dma_addr_t *dma_handle, void **vaddr_handle, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8166c650)
Location: drivers/usb/core/hcd.c:1378
Inline: True
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
**Symbols:**

```
ffffffff8166c650-ffffffff8166c6ee: hcd_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int hcd_alloc_coherent(struct usb_bus *bus, gfp_t mem_flags, dma_addr_t *dma_handle, void **vaddr_handle, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8169a350)
Location: drivers/usb/core/hcd.c:1379
Inline: True
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
**Symbols:**

```
ffffffff8169a350-ffffffff8169a3ee: hcd_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int hcd_alloc_coherent(struct usb_bus *bus, gfp_t mem_flags, dma_addr_t *dma_handle, void **vaddr_handle, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff816af1e0)
Location: drivers/usb/core/hcd.c:1382
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
**Symbols:**

```
ffffffff816af1e0-ffffffff816af24c: hcd_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int hcd_alloc_coherent(struct usb_bus *bus, gfp_t mem_flags, dma_addr_t *dma_handle, void **vaddr_handle, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8171a7d0)
Location: drivers/usb/core/hcd.c:1371
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
**Symbols:**

```
ffffffff8171a7d0-ffffffff8171a83d: hcd_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int hcd_alloc_coherent(struct usb_bus *bus, gfp_t mem_flags, dma_addr_t *dma_handle, void **vaddr_handle, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81759500)
Location: drivers/usb/core/hcd.c:1373
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
**Symbols:**

```
ffffffff81759500-ffffffff8175956d: hcd_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int hcd_alloc_coherent(struct usb_bus *bus, gfp_t mem_flags, dma_addr_t *dma_handle, void **vaddr_handle, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8177da70)
Location: drivers/usb/core/hcd.c:1371
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
**Symbols:**

```
ffffffff8177da70-ffffffff8177dadd: hcd_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int hcd_alloc_coherent(struct usb_bus *bus, gfp_t mem_flags, dma_addr_t *dma_handle, void **vaddr_handle, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817bc0a0)
Location: drivers/usb/core/hcd.c:1273
Inline: True
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
**Symbols:**

```
ffffffff817bc0a0-ffffffff817bc10f: hcd_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int hcd_alloc_coherent(struct usb_bus *bus, gfp_t mem_flags, dma_addr_t *dma_handle, void **vaddr_handle, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817ec8d0)
Location: drivers/usb/core/hcd.c:1270
Inline: True
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
**Symbols:**

```
ffffffff817ec8d0-ffffffff817ec93f: hcd_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int hcd_alloc_coherent(struct usb_bus *bus, gfp_t mem_flags, dma_addr_t *dma_handle, void **vaddr_handle, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff818bbcc0)
Location: drivers/usb/core/hcd.c:1271
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
**Symbols:**

```
ffffffff818bbcc0-ffffffff818bbd2f: hcd_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int hcd_alloc_coherent(struct usb_bus *bus, gfp_t mem_flags, dma_addr_t *dma_handle, void **vaddr_handle, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff818c8a80)
Location: drivers/usb/core/hcd.c:1272
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
**Symbols:**

```
ffffffff818c8a80-ffffffff818c8aef: hcd_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int hcd_alloc_coherent(struct usb_bus *bus, gfp_t mem_flags, dma_addr_t *dma_handle, void **vaddr_handle, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff818ac0c0)
Location: drivers/usb/core/hcd.c:1272
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
**Symbols:**

```
ffffffff818ac0c0-ffffffff818ac12f: hcd_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int hcd_alloc_coherent(struct usb_bus *bus, gfp_t mem_flags, dma_addr_t *dma_handle, void **vaddr_handle, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81941110)
Location: drivers/usb/core/hcd.c:1279
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
**Symbols:**

```
ffffffff81941110-ffffffff8194117f: hcd_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int hcd_alloc_coherent(struct usb_bus *bus, gfp_t mem_flags, dma_addr_t *dma_handle, void **vaddr_handle, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81a995a0)
Location: drivers/usb/core/hcd.c:1279
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
**Symbols:**

```
ffffffff81a995a0-ffffffff81a99633: hcd_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hcd_alloc_coherent(struct usb_bus *bus, gfp_t mem_flags, dma_addr_t *dma_handle, void **vaddr_handle, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81c1d9e0)
Location: drivers/usb/core/hcd.c:1280
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
**Symbols:**

```
ffffffff81c1d9e0-ffffffff81c1da73: hcd_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hcd_alloc_coherent(struct usb_bus *bus, gfp_t mem_flags, dma_addr_t *dma_handle, void **vaddr_handle, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81c848d0)
Location: drivers/usb/core/hcd.c:1284
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
**Symbols:**

```
ffffffff81c848d0-ffffffff81c84963: hcd_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hcd_alloc_coherent(struct usb_bus *bus, gfp_t mem_flags, dma_addr_t *dma_handle, void **vaddr_handle, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81d392d0)
Location: drivers/usb/core/hcd.c:1259
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
**Symbols:**

```
ffffffff81d392d0-ffffffff81d39363: hcd_alloc_coherent (STB_LOCAL)
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
int hcd_alloc_coherent(struct usb_bus *bus, gfp_t mem_flags, dma_addr_t *dma_handle, void **vaddr_handle, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffff800010a1ba28)
Location: drivers/usb/core/hcd.c:1270
Inline: True
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
**Symbols:**

```
ffff800010a1ba28-ffff800010a1bacc: hcd_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int hcd_alloc_coherent(struct usb_bus *bus, gfp_t mem_flags, dma_addr_t *dma_handle, void **vaddr_handle, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (c0af39cc)
Location: drivers/usb/core/hcd.c:1270
Inline: True
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
**Symbols:**

```
c0af39cc-c0af3a80: hcd_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int hcd_alloc_coherent(struct usb_bus *bus, gfp_t mem_flags, dma_addr_t *dma_handle, void **vaddr_handle, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (c000000000ad4ec0)
Location: drivers/usb/core/hcd.c:1270
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
**Symbols:**

```
c000000000ad4ec0-c000000000ad4f7c: hcd_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffe0006413f8)
Location: drivers/usb/core/hcd.c:1270
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
**Symbols:**

```
ffffffe00063ff98-ffffffe00063ffb6: hcd_alloc_coherent.part.0 (STB_LOCAL)
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
int hcd_alloc_coherent(struct usb_bus *bus, gfp_t mem_flags, dma_addr_t *dma_handle, void **vaddr_handle, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817a4cb0)
Location: drivers/usb/core/hcd.c:1270
Inline: True
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
**Symbols:**

```
ffffffff817a4cb0-ffffffff817a4d1f: hcd_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int hcd_alloc_coherent(struct usb_bus *bus, gfp_t mem_flags, dma_addr_t *dma_handle, void **vaddr_handle, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817967c0)
Location: drivers/usb/core/hcd.c:1270
Inline: True
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
**Symbols:**

```
ffffffff817967c0-ffffffff8179682f: hcd_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int hcd_alloc_coherent(struct usb_bus *bus, gfp_t mem_flags, dma_addr_t *dma_handle, void **vaddr_handle, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817e1750)
Location: drivers/usb/core/hcd.c:1270
Inline: True
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
**Symbols:**

```
ffffffff817e1750-ffffffff817e17bf: hcd_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int hcd_alloc_coherent(struct usb_bus *bus, gfp_t mem_flags, dma_addr_t *dma_handle, void **vaddr_handle, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817fbb40)
Location: drivers/usb/core/hcd.c:1270
Inline: True
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
**Symbols:**

```
ffffffff817fbb40-ffffffff817fbbaf: hcd_alloc_coherent (STB_LOCAL)
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
