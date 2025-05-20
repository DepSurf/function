# Function: <code>vm_insert_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int vm_insert_page(struct vm_area_struct *vma, long unsigned int addr, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811c1900)
Location: mm/memory.c:1503
Inline: False
Direct callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - net/netlink/af_netlink.c:netlink_mmap
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:packet_mmap
```
**Symbols:**

```
ffffffff811c1900-ffffffff811c1ad2: vm_insert_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int vm_insert_page(struct vm_area_struct *vma, long unsigned int addr, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811dd3d0)
Location: mm/memory.c:1536
Inline: False
Direct callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:packet_mmap
```
**Symbols:**

```
ffffffff811dd3d0-ffffffff811dd5dd: vm_insert_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int vm_insert_page(struct vm_area_struct *vma, long unsigned int addr, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811ecec0)
Location: mm/memory.c:1532
Inline: False
Direct callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:packet_mmap
```
**Symbols:**

```
ffffffff811ecec0-ffffffff811ed0ca: vm_insert_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int vm_insert_page(struct vm_area_struct *vma, long unsigned int addr, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f7e00)
Location: mm/memory.c:1662
Inline: False
Direct callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - net/packet/af_packet.c:packet_mmap
```
**Symbols:**

```
ffffffff811f7e00-ffffffff811f7fe3: vm_insert_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int vm_insert_page(struct vm_area_struct *vma, long unsigned int addr, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8120ff70)
Location: mm/memory.c:1765
Inline: False
Direct callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - net/packet/af_packet.c:packet_mmap
```
**Symbols:**

```
ffffffff8120ff70-ffffffff81210153: vm_insert_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int vm_insert_page(struct vm_area_struct *vma, long unsigned int addr, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8122f640)
Location: mm/memory.c:1776
Inline: False
Direct callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:packet_mmap
```
**Symbols:**

```
ffffffff8122f640-ffffffff8122f837: vm_insert_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int vm_insert_page(struct vm_area_struct *vma, long unsigned int addr, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81244030)
Location: mm/memory.c:1508
Inline: False
Direct callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:packet_mmap
```
**Symbols:**

```
ffffffff81244030-ffffffff81244229: vm_insert_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int vm_insert_page(struct vm_area_struct *vma, long unsigned int addr, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81255ec0)
Location: mm/memory.c:1480
Inline: False
Direct callers:
  - mm/memory.c:__vm_map_pages
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:packet_mmap
```
**Symbols:**

```
ffffffff81255ec0-ffffffff812560f2: vm_insert_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int vm_insert_page(struct vm_area_struct *vma, long unsigned int addr, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81264450)
Location: mm/memory.c:1485
Inline: False
Direct callers:
  - mm/memory.c:__vm_map_pages
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:packet_mmap
```
**Symbols:**

```
ffffffff81264450-ffffffff81264682: vm_insert_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vm_insert_page(struct vm_area_struct *vma, long unsigned int addr, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81293040)
Location: mm/memory.c:1648
Inline: False
Direct callers:
  - mm/memory.c:__vm_map_pages
  - mm/memory.c:vm_insert_pages
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:packet_mmap
```
**Symbols:**

```
ffffffff81293040-ffffffff812930d4: vm_insert_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vm_insert_page(struct vm_area_struct *vma, long unsigned int addr, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129d8d0)
Location: mm/memory.c:1822
Inline: False
Direct callers:
  - mm/memory.c:__vm_map_pages
  - mm/memory.c:vm_insert_pages
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:packet_mmap
```
**Symbols:**

```
ffffffff8129d8d0-ffffffff8129d9a8: vm_insert_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vm_insert_page(struct vm_area_struct *vma, long unsigned int addr, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a2d80)
Location: mm/memory.c:1840
Inline: False
Direct callers:
  - mm/memory.c:__vm_map_pages
  - mm/memory.c:vm_insert_pages
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:packet_mmap
```
**Symbols:**

```
ffffffff812a2d80-ffffffff812a2f74: vm_insert_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vm_insert_page(struct vm_area_struct *vma, long unsigned int addr, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812e61f0)
Location: mm/memory.c:1935
Inline: False
Direct callers:
  - mm/memory.c:__vm_map_pages
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:packet_mmap
```
**Symbols:**

```
ffffffff812e61f0-ffffffff812e6349: vm_insert_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vm_insert_page(struct vm_area_struct *vma, long unsigned int addr, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81345170)
Location: mm/memory.c:2028
Inline: False
Direct callers:
  - mm/memory.c:__vm_map_pages
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:packet_mmap
```
**Symbols:**

```
ffffffff81345170-ffffffff813452e2: vm_insert_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vm_insert_page(struct vm_area_struct *vma, long unsigned int addr, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813bd3d0)
Location: mm/memory.c:1999
Inline: False
Direct callers:
  - mm/memory.c:__vm_map_pages
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:packet_mmap
```
**Symbols:**

```
ffffffff813bd3d0-ffffffff813bd548: vm_insert_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vm_insert_page(struct vm_area_struct *vma, long unsigned int addr, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813f2080)
Location: mm/memory.c:2019
Inline: False
Direct callers:
  - mm/memory.c:__vm_map_pages
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:packet_mmap
```
**Symbols:**

```
ffffffff813f2080-ffffffff813f2220: vm_insert_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vm_insert_page(struct vm_area_struct *vma, long unsigned int addr, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8141cd00)
Location: mm/memory.c:2042
Inline: False
Direct callers:
  - mm/memory.c:__vm_map_pages
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:packet_mmap
```
**Symbols:**

```
ffffffff8141cd00-ffffffff8141cea1: vm_insert_page (STB_GLOBAL)
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
int vm_insert_page(struct vm_area_struct *vma, long unsigned int addr, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102fb140)
Location: mm/memory.c:1485
Inline: False
Direct callers:
  - mm/memory.c:__vm_map_pages
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:packet_mmap
```
**Symbols:**

```
ffff8000102fb140-ffff8000102fb3b4: vm_insert_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int vm_insert_page(struct vm_area_struct *vma, long unsigned int addr, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0519bb4)
Location: mm/memory.c:1485
Inline: False
Direct callers:
  - mm/memory.c:__vm_map_pages
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - net/packet/af_packet.c:packet_mmap
```
**Symbols:**

```
c0519bb4-c0519c6c: vm_insert_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vm_insert_page(struct vm_area_struct *vma, long unsigned int addr, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003c5e80)
Location: mm/memory.c:1485
Inline: False
Direct callers:
  - mm/memory.c:__vm_map_pages
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:packet_mmap
```
**Symbols:**

```
c0000000003c5e80-c0000000003c626c: vm_insert_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int vm_insert_page(struct vm_area_struct *vma, long unsigned int addr, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe00020a918)
Location: mm/memory.c:1485
Inline: False
Direct callers:
  - mm/memory.c:__vm_map_pages
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:packet_mmap
```
**Symbols:**

```
ffffffe00020a918-ffffffe00020ab1e: vm_insert_page (STB_GLOBAL)
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
int vm_insert_page(struct vm_area_struct *vma, long unsigned int addr, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125caa0)
Location: mm/memory.c:1485
Inline: False
Direct callers:
  - mm/memory.c:__vm_map_pages
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:packet_mmap
```
**Symbols:**

```
ffffffff8125caa0-ffffffff8125ccd2: vm_insert_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int vm_insert_page(struct vm_area_struct *vma, long unsigned int addr, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124ef80)
Location: mm/memory.c:1485
Inline: False
Direct callers:
  - mm/memory.c:__vm_map_pages
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:packet_mmap
```
**Symbols:**

```
ffffffff8124ef80-ffffffff8124f193: vm_insert_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vm_insert_page(struct vm_area_struct *vma, long unsigned int addr, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125a840)
Location: mm/memory.c:1485
Inline: False
Direct callers:
  - mm/memory.c:__vm_map_pages
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:packet_mmap
```
**Symbols:**

```
ffffffff8125a840-ffffffff8125aa72: vm_insert_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vm_insert_page(struct vm_area_struct *vma, long unsigned int addr, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8126a220)
Location: mm/memory.c:1485
Inline: False
Direct callers:
  - mm/memory.c:__vm_map_pages
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:packet_mmap
```
**Symbols:**

```
ffffffff8126a220-ffffffff8126a44b: vm_insert_page (STB_GLOBAL)
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
