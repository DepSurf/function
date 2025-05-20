# Function: <code>vma_wants_writenotify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int vma_wants_writenotify(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811c5c70)
Location: mm/mmap.c:1493
Inline: True
Direct callers:
  - mm/mmap.c:vma_set_page_prot
  - mm/mprotect.c:mprotect_fixup
```
**Symbols:**

```
ffffffff811c5c70-ffffffff811c5d43: vma_wants_writenotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int vma_wants_writenotify(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811e1a80)
Location: mm/mmap.c:1384
Inline: True
Direct callers:
  - mm/mmap.c:vma_set_page_prot
  - mm/mprotect.c:mprotect_fixup
```
**Symbols:**

```
ffffffff811e1a80-ffffffff811e1b5a: vma_wants_writenotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int vma_wants_writenotify(struct vm_area_struct *vma, pgprot_t vm_page_prot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811f1a70)
Location: mm/mmap.c:1537
Inline: True
Direct callers:
  - mm/mmap.c:vma_set_page_prot
  - mm/mprotect.c:mprotect_fixup
```
**Symbols:**

```
ffffffff811f1a70-ffffffff811f1b49: vma_wants_writenotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int vma_wants_writenotify(struct vm_area_struct *vma, pgprot_t vm_page_prot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811fc770)
Location: mm/mmap.c:1554
Inline: True
Direct callers:
  - mm/mmap.c:vma_set_page_prot
  - mm/mprotect.c:mprotect_fixup
```
**Symbols:**

```
ffffffff811fc770-ffffffff811fc857: vma_wants_writenotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int vma_wants_writenotify(struct vm_area_struct *vma, pgprot_t vm_page_prot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81214cb0)
Location: mm/mmap.c:1570
Inline: True
Direct callers:
  - mm/mmap.c:vma_set_page_prot
  - mm/mprotect.c:mprotect_fixup
```
**Symbols:**

```
ffffffff81214cb0-ffffffff81214db3: vma_wants_writenotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int vma_wants_writenotify(struct vm_area_struct *vma, pgprot_t vm_page_prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81235b30)
Location: mm/mmap.c:1629
Inline: False
Direct callers:
  - mm/mmap.c:vma_set_page_prot
  - mm/mprotect.c:mprotect_fixup
```
**Symbols:**

```
ffffffff81235b30-ffffffff81235c30: vma_wants_writenotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int vma_wants_writenotify(struct vm_area_struct *vma, pgprot_t vm_page_prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81249330)
Location: mm/mmap.c:1653
Inline: False
Direct callers:
  - mm/mmap.c:vma_set_page_prot
  - mm/mprotect.c:mprotect_fixup
```
**Symbols:**

```
ffffffff81249330-ffffffff8124943d: vma_wants_writenotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int vma_wants_writenotify(struct vm_area_struct *vma, pgprot_t vm_page_prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8125b640)
Location: mm/mmap.c:1655
Inline: False
Direct callers:
  - mm/mmap.c:vma_set_page_prot
  - mm/mprotect.c:mprotect_fixup
```
**Symbols:**

```
ffffffff8125b640-ffffffff8125b754: vma_wants_writenotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int vma_wants_writenotify(struct vm_area_struct *vma, pgprot_t vm_page_prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81269d20)
Location: mm/mmap.c:1663
Inline: False
Direct callers:
  - mm/mmap.c:vma_set_page_prot
  - mm/mprotect.c:mprotect_fixup
```
**Symbols:**

```
ffffffff81269d20-ffffffff81269e34: vma_wants_writenotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vma_wants_writenotify(struct vm_area_struct *vma, pgprot_t vm_page_prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8129a550)
Location: mm/mmap.c:1639
Inline: False
Direct callers:
  - mm/mmap.c:vma_set_page_prot
  - mm/mprotect.c:mprotect_fixup
```
**Symbols:**

```
ffffffff8129a550-ffffffff8129a667: vma_wants_writenotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vma_wants_writenotify(struct vm_area_struct *vma, pgprot_t vm_page_prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812a5730)
Location: mm/mmap.c:1678
Inline: False
Direct callers:
  - mm/mmap.c:vma_set_page_prot
  - mm/mprotect.c:mprotect_fixup
```
**Symbols:**

```
ffffffff812a5730-ffffffff812a5843: vma_wants_writenotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vma_wants_writenotify(struct vm_area_struct *vma, pgprot_t vm_page_prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812aaec0)
Location: mm/mmap.c:1682
Inline: False
Direct callers:
  - mm/mmap.c:vma_set_page_prot
  - mm/mprotect.c:mprotect_fixup
```
**Symbols:**

```
ffffffff812aaec0-ffffffff812aafd9: vma_wants_writenotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vma_wants_writenotify(struct vm_area_struct *vma, pgprot_t vm_page_prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812ec590)
Location: mm/mmap.c:1668
Inline: False
Direct callers:
  - mm/mmap.c:vma_set_page_prot
  - mm/mprotect.c:mprotect_fixup
```
**Symbols:**

```
ffffffff812ec590-ffffffff812ec6b0: vma_wants_writenotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vma_wants_writenotify(struct vm_area_struct *vma, pgprot_t vm_page_prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8134f480)
Location: mm/mmap.c:1677
Inline: False
Direct callers:
  - mm/mmap.c:vma_set_page_prot
  - mm/mprotect.c:mprotect_fixup
```
**Symbols:**

```
ffffffff8134f480-ffffffff8134f575: vma_wants_writenotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vma_wants_writenotify(struct vm_area_struct *vma, pgprot_t vm_page_prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813c8aa0)
Location: mm/mmap.c:1501
Inline: False
Direct callers:
  - mm/memory.c:do_numa_page
  - mm/mmap.c:vma_set_page_prot
  - mm/mprotect.c:mprotect_fixup
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff813c8aa0-ffffffff813c8b96: vma_wants_writenotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vma_wants_writenotify(struct vm_area_struct *vma, pgprot_t vm_page_prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813fcd40)
Location: mm/mmap.c:1492
Inline: False
Direct callers:
  - mm/memory.c:do_numa_page
  - mm/mmap.c:vma_set_page_prot
  - mm/mprotect.c:mprotect_fixup
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/userfaultfd.c:uffd_wp_range
```
**Symbols:**

```
ffffffff813fcd40-ffffffff813fce25: vma_wants_writenotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vma_wants_writenotify(struct vm_area_struct *vma, pgprot_t vm_page_prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81429710)
Location: mm/mmap.c:1519
Inline: False
Direct callers:
  - mm/memory.c:do_numa_page
  - mm/mmap.c:vma_set_page_prot
  - mm/mprotect.c:mprotect_fixup
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/userfaultfd.c:uffd_wp_range
```
**Symbols:**

```
ffffffff81429710-ffffffff814297f5: vma_wants_writenotify (STB_GLOBAL)
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
int vma_wants_writenotify(struct vm_area_struct *vma, pgprot_t vm_page_prot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffff800010301108)
Location: mm/mmap.c:1663
Inline: True
Direct callers:
  - mm/mmap.c:vma_set_page_prot
  - mm/mprotect.c:mprotect_fixup
```
**Symbols:**

```
ffff800010301108-ffff8000103011dc: vma_wants_writenotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int vma_wants_writenotify(struct vm_area_struct *vma, pgprot_t vm_page_prot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c051fbf4)
Location: mm/mmap.c:1663
Inline: True
Direct callers:
  - mm/mmap.c:vma_set_page_prot
  - mm/mprotect.c:mprotect_fixup
```
**Symbols:**

```
c051fbf4-c051fd0c: vma_wants_writenotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int vma_wants_writenotify(struct vm_area_struct *vma, pgprot_t vm_page_prot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c0000000003cd480)
Location: mm/mmap.c:1663
Inline: True
Direct callers:
  - mm/mmap.c:vma_set_page_prot
  - mm/mprotect.c:mprotect_fixup
```
**Symbols:**

```
c0000000003cd480-c0000000003cd5c0: vma_wants_writenotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int vma_wants_writenotify(struct vm_area_struct *vma, pgprot_t vm_page_prot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffe00020e60a)
Location: mm/mmap.c:1663
Inline: True
Direct callers:
  - mm/mmap.c:vma_set_page_prot
  - mm/mprotect.c:mprotect_fixup
```
**Symbols:**

```
ffffffe00020e60a-ffffffe00020e6aa: vma_wants_writenotify (STB_GLOBAL)
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
int vma_wants_writenotify(struct vm_area_struct *vma, pgprot_t vm_page_prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81262370)
Location: mm/mmap.c:1663
Inline: False
Direct callers:
  - mm/mmap.c:vma_set_page_prot
  - mm/mprotect.c:mprotect_fixup
```
**Symbols:**

```
ffffffff81262370-ffffffff81262484: vma_wants_writenotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int vma_wants_writenotify(struct vm_area_struct *vma, pgprot_t vm_page_prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81254790)
Location: mm/mmap.c:1663
Inline: False
Direct callers:
  - mm/mmap.c:vma_set_page_prot
  - mm/mprotect.c:mprotect_fixup
```
**Symbols:**

```
ffffffff81254790-ffffffff812548a4: vma_wants_writenotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vma_wants_writenotify(struct vm_area_struct *vma, pgprot_t vm_page_prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81260110)
Location: mm/mmap.c:1663
Inline: False
Direct callers:
  - mm/mmap.c:vma_set_page_prot
  - mm/mprotect.c:mprotect_fixup
```
**Symbols:**

```
ffffffff81260110-ffffffff81260224: vma_wants_writenotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vma_wants_writenotify(struct vm_area_struct *vma, pgprot_t vm_page_prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8126fae0)
Location: mm/mmap.c:1663
Inline: False
Direct callers:
  - mm/mmap.c:vma_set_page_prot
  - mm/mprotect.c:mprotect_fixup
```
**Symbols:**

```
ffffffff8126fae0-ffffffff8126fbf4: vma_wants_writenotify (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>pgprot_t vm_page_prot</code>
</li>
</ul>
</details>
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
