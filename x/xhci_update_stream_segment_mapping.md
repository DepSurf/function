# Function: <code>xhci_update_stream_segment_mapping</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int xhci_update_stream_segment_mapping(struct radix_tree_root *trb_address_map, struct xhci_ring *ring, struct xhci_segment *first_seg, struct xhci_segment *last_seg, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81652cb0)
Location: drivers/usb/host/xhci-mem.c:215
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
**Symbols:**

```
ffffffff81652cb0-ffffffff81652d8a: xhci_update_stream_segment_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int xhci_update_stream_segment_mapping(struct radix_tree_root *trb_address_map, struct xhci_ring *ring, struct xhci_segment *first_seg, struct xhci_segment *last_seg, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816b3630)
Location: drivers/usb/host/xhci-mem.c:225
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
```
**Symbols:**

```
ffffffff816b3630-ffffffff816b3713: xhci_update_stream_segment_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int xhci_update_stream_segment_mapping(struct radix_tree_root *trb_address_map, struct xhci_ring *ring, struct xhci_segment *first_seg, struct xhci_segment *last_seg, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816e17e0)
Location: drivers/usb/host/xhci-mem.c:225
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
```
**Symbols:**

```
ffffffff816e17e0-ffffffff816e18c3: xhci_update_stream_segment_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int xhci_update_stream_segment_mapping(struct radix_tree_root *trb_address_map, struct xhci_ring *ring, struct xhci_segment *first_seg, struct xhci_segment *last_seg, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816f57d0)
Location: drivers/usb/host/xhci-mem.c:225
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
```
**Symbols:**

```
ffffffff816f57d0-ffffffff816f58aa: xhci_update_stream_segment_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int xhci_update_stream_segment_mapping(struct radix_tree_root *trb_address_map, struct xhci_ring *ring, struct xhci_segment *first_seg, struct xhci_segment *last_seg, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817621e0)
Location: drivers/usb/host/xhci-mem.c:214
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
```
**Symbols:**

```
ffffffff817621e0-ffffffff817622ba: xhci_update_stream_segment_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int xhci_update_stream_segment_mapping(struct radix_tree_root *trb_address_map, struct xhci_ring *ring, struct xhci_segment *first_seg, struct xhci_segment *last_seg, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817a2ba0)
Location: drivers/usb/host/xhci-mem.c:216
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
```
**Symbols:**

```
ffffffff817a2ba0-ffffffff817a2c79: xhci_update_stream_segment_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int xhci_update_stream_segment_mapping(struct xarray *trb_address_map, struct xhci_ring *ring, struct xhci_segment *first_seg, struct xhci_segment *last_seg, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817c8e90)
Location: drivers/usb/host/xhci-mem.c:216
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
```
**Symbols:**

```
ffffffff817c8e90-ffffffff817c8f67: xhci_update_stream_segment_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int xhci_update_stream_segment_mapping(struct xarray *trb_address_map, struct xhci_ring *ring, struct xhci_segment *first_seg, struct xhci_segment *last_seg, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81808c40)
Location: drivers/usb/host/xhci-mem.c:216
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
```
**Symbols:**

```
ffffffff81808c40-ffffffff81808d17: xhci_update_stream_segment_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int xhci_update_stream_segment_mapping(struct xarray *trb_address_map, struct xhci_ring *ring, struct xhci_segment *first_seg, struct xhci_segment *last_seg, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81839b00)
Location: drivers/usb/host/xhci-mem.c:216
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
```
**Symbols:**

```
ffffffff81839b00-ffffffff81839bd7: xhci_update_stream_segment_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int xhci_update_stream_segment_mapping(struct xarray *trb_address_map, struct xhci_ring *ring, struct xhci_segment *first_seg, struct xhci_segment *last_seg, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8190c4f0)
Location: drivers/usb/host/xhci-mem.c:216
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
```
**Symbols:**

```
ffffffff8190c4f0-ffffffff8190c5da: xhci_update_stream_segment_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int xhci_update_stream_segment_mapping(struct xarray *trb_address_map, struct xhci_ring *ring, struct xhci_segment *first_seg, struct xhci_segment *last_seg, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81913f00)
Location: drivers/usb/host/xhci-mem.c:219
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
```
**Symbols:**

```
ffffffff81913f00-ffffffff81913fea: xhci_update_stream_segment_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int xhci_update_stream_segment_mapping(struct xarray *trb_address_map, struct xhci_ring *ring, struct xhci_segment *first_seg, struct xhci_segment *last_seg, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff818f7420)
Location: drivers/usb/host/xhci-mem.c:219
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
```
**Symbols:**

```
ffffffff818f7420-ffffffff818f750a: xhci_update_stream_segment_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81998ea1)
Location: drivers/usb/host/xhci-mem.c:219
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
```
**Symbols:**

```
ffffffff819959b0-ffffffff81995a8b: xhci_update_stream_segment_mapping.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xhci_update_stream_segment_mapping(struct xarray *trb_address_map, struct xhci_ring *ring, struct xhci_segment *first_seg, struct xhci_segment *last_seg, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81af2710)
Location: drivers/usb/host/xhci-mem.c:219
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
```
**Symbols:**

```
ffffffff81af2710-ffffffff81af281f: xhci_update_stream_segment_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xhci_update_stream_segment_mapping(struct xarray *trb_address_map, struct xhci_ring *ring, struct xhci_segment *first_seg, struct xhci_segment *last_seg, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81c7fbe0)
Location: drivers/usb/host/xhci-mem.c:219
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
```
**Symbols:**

```
ffffffff81c7fbe0-ffffffff81c7fcef: xhci_update_stream_segment_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xhci_update_stream_segment_mapping(struct xarray *trb_address_map, struct xhci_ring *ring, struct xhci_segment *first_seg, struct xhci_segment *last_seg, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81ce68c0)
Location: drivers/usb/host/xhci-mem.c:219
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
```
**Symbols:**

```
ffffffff81ce68c0-ffffffff81ce69cf: xhci_update_stream_segment_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xhci_update_stream_segment_mapping(struct xarray *trb_address_map, struct xhci_ring *ring, struct xhci_segment *first_seg, struct xhci_segment *last_seg, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81d9bb20)
Location: drivers/usb/host/xhci-mem.c:226
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
```
**Symbols:**

```
ffffffff81d9bb20-ffffffff81d9bc2f: xhci_update_stream_segment_mapping (STB_LOCAL)
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
int xhci_update_stream_segment_mapping(struct xarray *trb_address_map, struct xhci_ring *ring, struct xhci_segment *first_seg, struct xhci_segment *last_seg, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffff800010a77578)
Location: drivers/usb/host/xhci-mem.c:216
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
```
**Symbols:**

```
ffff800010a77578-ffff800010a776a4: xhci_update_stream_segment_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int xhci_update_stream_segment_mapping(struct xarray *trb_address_map, struct xhci_ring *ring, struct xhci_segment *first_seg, struct xhci_segment *last_seg, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (c0b4b1a8)
Location: drivers/usb/host/xhci-mem.c:216
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
```
**Symbols:**

```
c0b4b1a8-c0b4b2b8: xhci_update_stream_segment_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int xhci_update_stream_segment_mapping(struct xarray *trb_address_map, struct xhci_ring *ring, struct xhci_segment *first_seg, struct xhci_segment *last_seg, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (c000000000b4df60)
Location: drivers/usb/host/xhci-mem.c:216
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
```
**Symbols:**

```
c000000000b4df60-c000000000b4e0cc: xhci_update_stream_segment_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int xhci_update_stream_segment_mapping(struct xarray *trb_address_map, struct xhci_ring *ring, struct xhci_segment *first_seg, struct xhci_segment *last_seg, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffe00068f124)
Location: drivers/usb/host/xhci-mem.c:216
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
```
**Symbols:**

```
ffffffe00068f124-ffffffe00068f1d8: xhci_update_stream_segment_mapping (STB_LOCAL)
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
int xhci_update_stream_segment_mapping(struct xarray *trb_address_map, struct xhci_ring *ring, struct xhci_segment *first_seg, struct xhci_segment *last_seg, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817f1eb0)
Location: drivers/usb/host/xhci-mem.c:216
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
```
**Symbols:**

```
ffffffff817f1eb0-ffffffff817f1f87: xhci_update_stream_segment_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int xhci_update_stream_segment_mapping(struct xarray *trb_address_map, struct xhci_ring *ring, struct xhci_segment *first_seg, struct xhci_segment *last_seg, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817b7050)
Location: drivers/usb/host/xhci-mem.c:216
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
```
**Symbols:**

```
ffffffff817b7050-ffffffff817b7127: xhci_update_stream_segment_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int xhci_update_stream_segment_mapping(struct xarray *trb_address_map, struct xhci_ring *ring, struct xhci_segment *first_seg, struct xhci_segment *last_seg, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8182e980)
Location: drivers/usb/host/xhci-mem.c:216
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
```
**Symbols:**

```
ffffffff8182e980-ffffffff8182ea57: xhci_update_stream_segment_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int xhci_update_stream_segment_mapping(struct xarray *trb_address_map, struct xhci_ring *ring, struct xhci_segment *first_seg, struct xhci_segment *last_seg, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81848ad0)
Location: drivers/usb/host/xhci-mem.c:216
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
```
**Symbols:**

```
ffffffff81848ad0-ffffffff81848bb1: xhci_update_stream_segment_mapping (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct radix_tree_root *trb_address_map</code> ➡️ <code>struct xarray *trb_address_map</code>
</li>
</ul>
</details>
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
