# Function: <code>vmf_insert_mixed_mkwrite</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
vm_fault_t vmf_insert_mixed_mkwrite(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8122fc80)
Location: mm/memory.c:1979
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
```
**Symbols:**

```
ffffffff8122fc80-ffffffff8122fcb6: vmf_insert_mixed_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
vm_fault_t vmf_insert_mixed_mkwrite(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812446b0)
Location: mm/memory.c:1722
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
```
**Symbols:**

```
ffffffff812446b0-ffffffff812446c5: vmf_insert_mixed_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
vm_fault_t vmf_insert_mixed_mkwrite(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81256670)
Location: mm/memory.c:1775
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
```
**Symbols:**

```
ffffffff81256670-ffffffff81256685: vmf_insert_mixed_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
vm_fault_t vmf_insert_mixed_mkwrite(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81264c00)
Location: mm/memory.c:1780
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
```
**Symbols:**

```
ffffffff81264c00-ffffffff81264c15: vmf_insert_mixed_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
vm_fault_t vmf_insert_mixed_mkwrite(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81292e90)
Location: mm/memory.c:1979
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_iomap_pte_fault
```
**Symbols:**

```
ffffffff81292e90-ffffffff81292eaa: vmf_insert_mixed_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
vm_fault_t vmf_insert_mixed_mkwrite(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129d730)
Location: mm/memory.c:2153
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_iomap_pte_fault
```
**Symbols:**

```
ffffffff8129d730-ffffffff8129d74a: vmf_insert_mixed_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
vm_fault_t vmf_insert_mixed_mkwrite(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a2d60)
Location: mm/memory.c:2171
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_iomap_pte_fault
```
**Symbols:**

```
ffffffff812a2d60-ffffffff812a2d7a: vmf_insert_mixed_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
vm_fault_t vmf_insert_mixed_mkwrite(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812e61d0)
Location: mm/memory.c:2266
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_fault_iter
```
**Symbols:**

```
ffffffff812e61d0-ffffffff812e61ea: vmf_insert_mixed_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
vm_fault_t vmf_insert_mixed_mkwrite(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81345810)
Location: mm/memory.c:2359
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_fault_iter
```
**Symbols:**

```
ffffffff81345810-ffffffff81345839: vmf_insert_mixed_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
vm_fault_t vmf_insert_mixed_mkwrite(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813bdb90)
Location: mm/memory.c:2330
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_fault_iter
```
**Symbols:**

```
ffffffff813bdb90-ffffffff813bdbb9: vmf_insert_mixed_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
vm_fault_t vmf_insert_mixed_mkwrite(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813f2840)
Location: mm/memory.c:2330
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_fault_iter
```
**Symbols:**

```
ffffffff813f2840-ffffffff813f2861: vmf_insert_mixed_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
vm_fault_t vmf_insert_mixed_mkwrite(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8141d580)
Location: mm/memory.c:2353
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_fault_iter
```
**Symbols:**

```
ffffffff8141d580-ffffffff8141d5a1: vmf_insert_mixed_mkwrite (STB_GLOBAL)
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
vm_fault_t vmf_insert_mixed_mkwrite(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102fb8a8)
Location: mm/memory.c:1780
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
```
**Symbols:**

```
ffff8000102fb8a8-ffff8000102fb8f0: vmf_insert_mixed_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
vm_fault_t vmf_insert_mixed_mkwrite(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c051a0dc)
Location: mm/memory.c:1780
Inline: False
```
**Symbols:**

```
c051a0dc-c051a108: vmf_insert_mixed_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
vm_fault_t vmf_insert_mixed_mkwrite(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003c68c0)
Location: mm/memory.c:1780
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
```
**Symbols:**

```
c0000000003c68c0-c0000000003c68d8: vmf_insert_mixed_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
vm_fault_t vmf_insert_mixed_mkwrite(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe00020af2a)
Location: mm/memory.c:1780
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
```
**Symbols:**

```
ffffffe00020af2a-ffffffe00020af68: vmf_insert_mixed_mkwrite (STB_GLOBAL)
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
vm_fault_t vmf_insert_mixed_mkwrite(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125d250)
Location: mm/memory.c:1780
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
```
**Symbols:**

```
ffffffff8125d250-ffffffff8125d265: vmf_insert_mixed_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
vm_fault_t vmf_insert_mixed_mkwrite(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124f6b0)
Location: mm/memory.c:1780
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
```
**Symbols:**

```
ffffffff8124f6b0-ffffffff8124f6c5: vmf_insert_mixed_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
vm_fault_t vmf_insert_mixed_mkwrite(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125aff0)
Location: mm/memory.c:1780
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
```
**Symbols:**

```
ffffffff8125aff0-ffffffff8125b005: vmf_insert_mixed_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
vm_fault_t vmf_insert_mixed_mkwrite(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8126a9c0)
Location: mm/memory.c:1780
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
```
**Symbols:**

```
ffffffff8126a9c0-ffffffff8126a9d5: vmf_insert_mixed_mkwrite (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
