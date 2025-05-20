# Function: <code>vmf_insert_pfn_pmd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int vmf_insert_pfn_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, long unsigned int pfn, bool write);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff811f5ad0)
Location: mm/huge_memory.c:892
Inline: False
```
**Symbols:**

```
ffffffff811f5ad0-ffffffff811f5ce6: vmf_insert_pfn_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int vmf_insert_pfn_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, pfn_t pfn, bool write);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81213e10)
Location: mm/huge_memory.c:662
Inline: False
```
**Symbols:**

```
ffffffff81213e10-ffffffff8121400b: vmf_insert_pfn_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int vmf_insert_pfn_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, pfn_t pfn, bool write);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81226210)
Location: mm/huge_memory.c:733
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_pmd_fault
```
**Symbols:**

```
ffffffff81226210-ffffffff81226406: vmf_insert_pfn_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int vmf_insert_pfn_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, pfn_t pfn, bool write);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81231a10)
Location: mm/huge_memory.c:758
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_fault
```
**Symbols:**

```
ffffffff81231a10-ffffffff81231c00: vmf_insert_pfn_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int vmf_insert_pfn_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, pfn_t pfn, bool write);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8124f800)
Location: mm/huge_memory.c:758
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_iomap_fault
```
**Symbols:**

```
ffffffff8124f800-ffffffff8124f99d: vmf_insert_pfn_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, pfn_t pfn, bool write);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81273490)
Location: mm/huge_memory.c:755
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
```
**Symbols:**

```
ffffffff81273490-ffffffff81273679: vmf_insert_pfn_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, pfn_t pfn, bool write);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81287bb0)
Location: mm/huge_memory.c:774
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
```
**Symbols:**

```
ffffffff81287bb0-ffffffff81287da9: vmf_insert_pfn_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn_pmd(struct vm_fault *vmf, pfn_t pfn, bool write);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a26b0)
Location: mm/huge_memory.c:810
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
```
**Symbols:**

```
ffffffff812a26b0-ffffffff812a29c8: vmf_insert_pfn_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn_pmd(struct vm_fault *vmf, pfn_t pfn, bool write);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812b3ba0)
Location: mm/huge_memory.c:816
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
```
**Symbols:**

```
ffffffff812b3ba0-ffffffff812b3eb8: vmf_insert_pfn_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8138f112)
Location: include/linux/huge_mm.h:64
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_iomap_pmd_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813a079b)
Location: include/linux/huge_mm.h:55
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_iomap_pmd_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813a6ede)
Location: include/linux/huge_mm.h:55
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_iomap_pmd_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813f6d99)
Location: include/linux/huge_mm.h:55
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_fault_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff814699b7)
Location: include/linux/huge_mm.h:56
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_fault_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff814fa77f)
Location: include/linux/huge_mm.h:56
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_fault_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn_pmd(struct vm_fault *vmf, pfn_t pfn, bool write);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81472830)
Location: mm/huge_memory.c:897
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_fault_iter
```
**Symbols:**

```
ffffffff81472830-ffffffff81472b83: vmf_insert_pfn_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn_pmd(struct vm_fault *vmf, pfn_t pfn, bool write);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff814a29d0)
Location: mm/huge_memory.c:1112
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_fault_iter
```
**Symbols:**

```
ffffffff814a29d0-ffffffff814a2d59: vmf_insert_pfn_pmd (STB_GLOBAL)
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
vm_fault_t vmf_insert_pfn_pmd(struct vm_fault *vmf, pfn_t pfn, bool write);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffff800010354590)
Location: mm/huge_memory.c:816
Inline: False
```
**Symbols:**

```
ffff800010354590-ffff800010354810: vmf_insert_pfn_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn_pmd(struct vm_fault *vmf, pfn_t pfn, bool write);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (c00000000043b320)
Location: mm/huge_memory.c:816
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
```
**Symbols:**

```
c00000000043b320-c00000000043b770: vmf_insert_pfn_pmd (STB_GLOBAL)
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
vm_fault_t vmf_insert_pfn_pmd(struct vm_fault *vmf, pfn_t pfn, bool write);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812ac180)
Location: mm/huge_memory.c:816
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
```
**Symbols:**

```
ffffffff812ac180-ffffffff812ac498: vmf_insert_pfn_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn_pmd(struct vm_fault *vmf, pfn_t pfn, bool write);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8129d5b0)
Location: mm/huge_memory.c:816
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
  - drivers/dax/device.c:dev_dax_huge_fault
```
**Symbols:**

```
ffffffff8129d5b0-ffffffff8129d850: vmf_insert_pfn_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn_pmd(struct vm_fault *vmf, pfn_t pfn, bool write);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a9f90)
Location: mm/huge_memory.c:816
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
```
**Symbols:**

```
ffffffff812a9f90-ffffffff812aa2a8: vmf_insert_pfn_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn_pmd(struct vm_fault *vmf, pfn_t pfn, bool write);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812ba2b0)
Location: mm/huge_memory.c:816
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
```
**Symbols:**

```
ffffffff812ba2b0-ffffffff812ba5c9: vmf_insert_pfn_pmd (STB_GLOBAL)
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
<b>Param type changed. </b>
<code>long unsigned int pfn</code> ➡️ <code>pfn_t pfn</code>
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
<b>Return type changed. </b>
<code>int</code> ➡️ <code>vm_fault_t</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vm_fault *vmf</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vm_area_struct *vma</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int addr</code>
</li>
<li>
<b>Param removed. </b>
<code>pmd_t *pmd</code>
</li>
<li>
<b>Param reordered. </b>
<code>vma, addr, pmd, pfn, write</code> ➡️ <code>vmf, pfn, write</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
