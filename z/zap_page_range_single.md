# Function: <code>zap_page_range_single</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void zap_page_range_single(struct vm_area_struct *vma, long unsigned int address, long unsigned int size, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811bddb0)
Location: mm/memory.c:1380
Inline: False
Direct callers:
  - mm/memory.c:zap_vma_ptes
  - mm/memory.c:unmap_mapping_range
```
**Symbols:**

```
ffffffff811bddb0-ffffffff811bdeb8: zap_page_range_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void zap_page_range_single(struct vm_area_struct *vma, long unsigned int address, long unsigned int size, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811d95d0)
Location: mm/memory.c:1413
Inline: False
Direct callers:
  - mm/memory.c:unmap_mapping_range
  - mm/memory.c:zap_vma_ptes
```
**Symbols:**

```
ffffffff811d95d0-ffffffff811d96e9: zap_page_range_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void zap_page_range_single(struct vm_area_struct *vma, long unsigned int address, long unsigned int size, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811e89e0)
Location: mm/memory.c:1409
Inline: False
Direct callers:
  - mm/memory.c:unmap_mapping_range
  - mm/memory.c:zap_vma_ptes
```
**Symbols:**

```
ffffffff811e89e0-ffffffff811e8af9: zap_page_range_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void zap_page_range_single(struct vm_area_struct *vma, long unsigned int address, long unsigned int size, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f3c50)
Location: mm/memory.c:1531
Inline: False
Direct callers:
  - mm/memory.c:unmap_mapping_range
  - mm/memory.c:zap_vma_ptes
```
**Symbols:**

```
ffffffff811f3c50-ffffffff811f3d69: zap_page_range_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void zap_page_range_single(struct vm_area_struct *vma, long unsigned int address, long unsigned int size, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8120b910)
Location: mm/memory.c:1634
Inline: False
Direct callers:
  - mm/memory.c:unmap_mapping_range
  - mm/memory.c:zap_vma_ptes
```
**Symbols:**

```
ffffffff8120b910-ffffffff8120ba2b: zap_page_range_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void zap_page_range_single(struct vm_area_struct *vma, long unsigned int address, long unsigned int size, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8122c620)
Location: mm/memory.c:1646
Inline: False
Direct callers:
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:zap_vma_ptes
```
**Symbols:**

```
ffffffff8122c620-ffffffff8122c737: zap_page_range_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void zap_page_range_single(struct vm_area_struct *vma, long unsigned int address, long unsigned int size, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8123fc60)
Location: mm/memory.c:1378
Inline: False
Direct callers:
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:zap_vma_ptes
```
**Symbols:**

```
ffffffff8123fc60-ffffffff8123fda4: zap_page_range_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void zap_page_range_single(struct vm_area_struct *vma, long unsigned int address, long unsigned int size, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81251d90)
Location: mm/memory.c:1349
Inline: False
Direct callers:
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:zap_vma_ptes
```
**Symbols:**

```
ffffffff81251d90-ffffffff81251eee: zap_page_range_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void zap_page_range_single(struct vm_area_struct *vma, long unsigned int address, long unsigned int size, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81260340)
Location: mm/memory.c:1354
Inline: False
Direct callers:
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:zap_vma_ptes
```
**Symbols:**

```
ffffffff81260340-ffffffff812604b6: zap_page_range_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void zap_page_range_single(struct vm_area_struct *vma, long unsigned int address, long unsigned int size, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81290910)
Location: mm/memory.c:1382
Inline: False
Direct callers:
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:zap_vma_ptes
```
**Symbols:**

```
ffffffff81290910-ffffffff81290a86: zap_page_range_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void zap_page_range_single(struct vm_area_struct *vma, long unsigned int address, long unsigned int size, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129b3a0)
Location: mm/memory.c:1556
Inline: False
Direct callers:
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:zap_vma_ptes
```
**Symbols:**

```
ffffffff8129b3a0-ffffffff8129b516: zap_page_range_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void zap_page_range_single(struct vm_area_struct *vma, long unsigned int address, long unsigned int size, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a06b0)
Location: mm/memory.c:1574
Inline: False
Direct callers:
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:unmap_mapping_page
  - mm/memory.c:zap_vma_ptes
```
**Symbols:**

```
ffffffff812a06b0-ffffffff812a0817: zap_page_range_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void zap_page_range_single(struct vm_area_struct *vma, long unsigned int address, long unsigned int size, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812e1640)
Location: mm/memory.c:1669
Inline: False
Direct callers:
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:unmap_mapping_page
  - mm/memory.c:zap_vma_ptes
```
**Symbols:**

```
ffffffff812e1640-ffffffff812e17a7: zap_page_range_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void zap_page_range_single(struct vm_area_struct *vma, long unsigned int address, long unsigned int size, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81342180)
Location: mm/memory.c:1763
Inline: False
Direct callers:
  - mm/memory.c:unmap_mapping_range
  - mm/memory.c:unmap_mapping_folio
```
**Symbols:**

```
ffffffff81342180-ffffffff81342317: zap_page_range_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void zap_page_range_single(struct vm_area_struct *vma, long unsigned int address, long unsigned int size, struct zap_details *details);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813ba280)
Location: mm/memory.c:1726
Inline: False
Direct callers:
  - mm/memory.c:unmap_mapping_range
  - mm/memory.c:unmap_mapping_folio
  - mm/madvise.c:madvise_vma_behavior
```
**Symbols:**

```
ffffffff813ba280-ffffffff813ba43e: zap_page_range_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void zap_page_range_single(struct vm_area_struct *vma, long unsigned int address, long unsigned int size, struct zap_details *details);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813eec10)
Location: mm/memory.c:1741
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vdso_join_timens
  - mm/memory.c:unmap_mapping_range
  - mm/memory.c:unmap_mapping_folio
  - mm/madvise.c:madvise_vma_behavior
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_vm_insert_batch
```
**Symbols:**

```
ffffffff813eec10-ffffffff813eedf5: zap_page_range_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void zap_page_range_single(struct vm_area_struct *vma, long unsigned int address, long unsigned int size, struct zap_details *details);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8141a6c0)
Location: mm/memory.c:1775
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vdso_join_timens
  - mm/memory.c:unmap_mapping_range
  - mm/memory.c:unmap_mapping_folio
  - mm/madvise.c:madvise_vma_behavior
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_vm_insert_batch
```
**Symbols:**

```
ffffffff8141a6c0-ffffffff8141a8c5: zap_page_range_single (STB_GLOBAL)
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
void zap_page_range_single(struct vm_area_struct *vma, long unsigned int address, long unsigned int size, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102f7650)
Location: mm/memory.c:1354
Inline: False
Direct callers:
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:zap_vma_ptes
```
**Symbols:**

```
ffff8000102f7650-ffff8000102f77a4: zap_page_range_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void zap_page_range_single(struct vm_area_struct *vma, long unsigned int address, long unsigned int size, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c051964c)
Location: mm/memory.c:1354
Inline: False
Direct callers:
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:zap_vma_ptes
```
**Symbols:**

```
c051964c-c05197a8: zap_page_range_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void zap_page_range_single(struct vm_area_struct *vma, long unsigned int address, long unsigned int size, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003c0410)
Location: mm/memory.c:1354
Inline: False
Direct callers:
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:zap_vma_ptes
```
**Symbols:**

```
c0000000003c0410-c0000000003c05d4: zap_page_range_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void zap_page_range_single(struct vm_area_struct *vma, long unsigned int address, long unsigned int size, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe000207c62)
Location: mm/memory.c:1354
Inline: False
Direct callers:
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:zap_vma_ptes
```
**Symbols:**

```
ffffffe000207c62-ffffffe000207d8a: zap_page_range_single (STB_LOCAL)
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
void zap_page_range_single(struct vm_area_struct *vma, long unsigned int address, long unsigned int size, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81258990)
Location: mm/memory.c:1354
Inline: False
Direct callers:
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:zap_vma_ptes
```
**Symbols:**

```
ffffffff81258990-ffffffff81258b06: zap_page_range_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void zap_page_range_single(struct vm_area_struct *vma, long unsigned int address, long unsigned int size, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124ae50)
Location: mm/memory.c:1354
Inline: False
Direct callers:
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:zap_vma_ptes
```
**Symbols:**

```
ffffffff8124ae50-ffffffff8124afc6: zap_page_range_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void zap_page_range_single(struct vm_area_struct *vma, long unsigned int address, long unsigned int size, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81256730)
Location: mm/memory.c:1354
Inline: False
Direct callers:
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:zap_vma_ptes
```
**Symbols:**

```
ffffffff81256730-ffffffff812568a6: zap_page_range_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void zap_page_range_single(struct vm_area_struct *vma, long unsigned int address, long unsigned int size, struct zap_details *details);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812661d0)
Location: mm/memory.c:1354
Inline: False
Direct callers:
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:zap_vma_ptes
```
**Symbols:**

```
ffffffff812661d0-ffffffff8126632e: zap_page_range_single (STB_LOCAL)
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
