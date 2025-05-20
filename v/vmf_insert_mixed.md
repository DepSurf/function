# Function: <code>vmf_insert_mixed</code>

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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff812f999f)
Location: include/linux/mm.h:2534
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
vm_fault_t vmf_insert_mixed(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81244690)
Location: mm/memory.c:1710
Inline: False
```
**Symbols:**

```
ffffffff81244690-ffffffff812446a2: vmf_insert_mixed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
vm_fault_t vmf_insert_mixed(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81256650)
Location: mm/memory.c:1763
Inline: False
```
**Symbols:**

```
ffffffff81256650-ffffffff81256662: vmf_insert_mixed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
vm_fault_t vmf_insert_mixed(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81264be0)
Location: mm/memory.c:1768
Inline: False
```
**Symbols:**

```
ffffffff81264be0-ffffffff81264bf2: vmf_insert_mixed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
vm_fault_t vmf_insert_mixed(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81292e70)
Location: mm/memory.c:1967
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_load_hole
```
**Symbols:**

```
ffffffff81292e70-ffffffff81292e87: vmf_insert_mixed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
vm_fault_t vmf_insert_mixed(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129d710)
Location: mm/memory.c:2141
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_load_hole
```
**Symbols:**

```
ffffffff8129d710-ffffffff8129d727: vmf_insert_mixed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
vm_fault_t vmf_insert_mixed(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a2d40)
Location: mm/memory.c:2159
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_iomap_pte_fault
```
**Symbols:**

```
ffffffff812a2d40-ffffffff812a2d57: vmf_insert_mixed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
vm_fault_t vmf_insert_mixed(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812e61b0)
Location: mm/memory.c:2254
Inline: False
Direct callers:
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_fault_iter
```
**Symbols:**

```
ffffffff812e61b0-ffffffff812e61c7: vmf_insert_mixed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
vm_fault_t vmf_insert_mixed(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813457e0)
Location: mm/memory.c:2347
Inline: False
Direct callers:
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_fault_iter
```
**Symbols:**

```
ffffffff813457e0-ffffffff81345806: vmf_insert_mixed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
vm_fault_t vmf_insert_mixed(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813bdb50)
Location: mm/memory.c:2318
Inline: False
Direct callers:
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_fault_iter
```
**Symbols:**

```
ffffffff813bdb50-ffffffff813bdb76: vmf_insert_mixed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
vm_fault_t vmf_insert_mixed(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813f2810)
Location: mm/memory.c:2318
Inline: False
Direct callers:
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_fault_iter
```
**Symbols:**

```
ffffffff813f2810-ffffffff813f282e: vmf_insert_mixed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
vm_fault_t vmf_insert_mixed(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8141d550)
Location: mm/memory.c:2341
Inline: False
Direct callers:
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_fault_iter
```
**Symbols:**

```
ffffffff8141d550-ffffffff8141d56e: vmf_insert_mixed (STB_GLOBAL)
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
vm_fault_t vmf_insert_mixed(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102fb860)
Location: mm/memory.c:1768
Inline: False
```
**Symbols:**

```
ffff8000102fb860-ffff8000102fb8a8: vmf_insert_mixed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
vm_fault_t vmf_insert_mixed(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c051a0b0)
Location: mm/memory.c:1768
Inline: False
```
**Symbols:**

```
c051a0b0-c051a0dc: vmf_insert_mixed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
vm_fault_t vmf_insert_mixed(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003c68a0)
Location: mm/memory.c:1768
Inline: False
```
**Symbols:**

```
c0000000003c68a0-c0000000003c68b8: vmf_insert_mixed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
vm_fault_t vmf_insert_mixed(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe00020aeec)
Location: mm/memory.c:1768
Inline: False
```
**Symbols:**

```
ffffffe00020aeec-ffffffe00020af2a: vmf_insert_mixed (STB_GLOBAL)
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
vm_fault_t vmf_insert_mixed(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125d230)
Location: mm/memory.c:1768
Inline: False
```
**Symbols:**

```
ffffffff8125d230-ffffffff8125d242: vmf_insert_mixed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
vm_fault_t vmf_insert_mixed(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124f690)
Location: mm/memory.c:1768
Inline: False
Direct callers:
  - drivers/dax/device.c:dev_dax_huge_fault
```
**Symbols:**

```
ffffffff8124f690-ffffffff8124f6a2: vmf_insert_mixed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
vm_fault_t vmf_insert_mixed(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125afd0)
Location: mm/memory.c:1768
Inline: False
```
**Symbols:**

```
ffffffff8125afd0-ffffffff8125afe2: vmf_insert_mixed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
vm_fault_t vmf_insert_mixed(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8126a9a0)
Location: mm/memory.c:1768
Inline: False
```
**Symbols:**

```
ffffffff8126a9a0-ffffffff8126a9b2: vmf_insert_mixed (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
