# Function: <code>__vm_insert_mixed</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int __vm_insert_mixed(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn, bool mkwrite);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f8280)
Location: mm/memory.c:1797
Inline: True
Direct callers:
  - mm/memory.c:vm_insert_mixed_mkwrite
  - mm/memory.c:vm_insert_mixed
```
**Symbols:**

```
ffffffff811f8280-ffffffff811f8311: __vm_insert_mixed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __vm_insert_mixed(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn, bool mkwrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81210400)
Location: mm/memory.c:1914
Inline: False
Direct callers:
  - mm/memory.c:vm_insert_mixed_mkwrite
  - mm/memory.c:vm_insert_mixed
```
**Symbols:**

```
ffffffff81210400-ffffffff812104c3: __vm_insert_mixed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __vm_insert_mixed(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn, bool mkwrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8122fb60)
Location: mm/memory.c:1928
Inline: False
Direct callers:
  - mm/memory.c:vmf_insert_mixed_mkwrite
  - mm/memory.c:vm_insert_mixed
```
**Symbols:**

```
ffffffff8122fb60-ffffffff8122fc54: __vm_insert_mixed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
vm_fault_t __vm_insert_mixed(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn, bool mkwrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812445a0)
Location: mm/memory.c:1664
Inline: False
Direct callers:
  - mm/memory.c:vmf_insert_mixed_mkwrite
  - mm/memory.c:vmf_insert_mixed
```
**Symbols:**

```
ffffffff812445a0-ffffffff8124468d: __vm_insert_mixed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
vm_fault_t __vm_insert_mixed(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn, bool mkwrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81256560)
Location: mm/memory.c:1717
Inline: False
Direct callers:
  - mm/memory.c:vmf_insert_mixed_mkwrite
  - mm/memory.c:vmf_insert_mixed
```
**Symbols:**

```
ffffffff81256560-ffffffff81256650: __vm_insert_mixed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
vm_fault_t __vm_insert_mixed(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn, bool mkwrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81264af0)
Location: mm/memory.c:1722
Inline: False
Direct callers:
  - mm/memory.c:vmf_insert_mixed_mkwrite
  - mm/memory.c:vmf_insert_mixed
```
**Symbols:**

```
ffffffff81264af0-ffffffff81264be0: __vm_insert_mixed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
vm_fault_t __vm_insert_mixed(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn, pgprot_t pgprot, bool mkwrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81292d70)
Location: mm/memory.c:1888
Inline: False
Direct callers:
  - mm/memory.c:vmf_insert_mixed_mkwrite
  - mm/memory.c:vmf_insert_mixed
  - mm/memory.c:vmf_insert_mixed_prot
```
**Symbols:**

```
ffffffff81292d70-ffffffff81292e44: __vm_insert_mixed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
vm_fault_t __vm_insert_mixed(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn, pgprot_t pgprot, bool mkwrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129d610)
Location: mm/memory.c:2062
Inline: False
Direct callers:
  - mm/memory.c:vmf_insert_mixed_mkwrite
  - mm/memory.c:vmf_insert_mixed
  - mm/memory.c:vmf_insert_mixed_prot
```
**Symbols:**

```
ffffffff8129d610-ffffffff8129d6e4: __vm_insert_mixed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
vm_fault_t __vm_insert_mixed(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn, pgprot_t pgprot, bool mkwrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a2c40)
Location: mm/memory.c:2080
Inline: False
Direct callers:
  - mm/memory.c:vmf_insert_mixed_mkwrite
  - mm/memory.c:vmf_insert_mixed
  - mm/memory.c:vmf_insert_mixed_prot
```
**Symbols:**

```
ffffffff812a2c40-ffffffff812a2d17: __vm_insert_mixed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
vm_fault_t __vm_insert_mixed(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn, pgprot_t pgprot, bool mkwrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812e60b0)
Location: mm/memory.c:2175
Inline: False
Direct callers:
  - mm/memory.c:vmf_insert_mixed_mkwrite
  - mm/memory.c:vmf_insert_mixed
  - mm/memory.c:vmf_insert_mixed_prot
```
**Symbols:**

```
ffffffff812e60b0-ffffffff812e6187: __vm_insert_mixed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
vm_fault_t __vm_insert_mixed(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn, pgprot_t pgprot, bool mkwrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813456b0)
Location: mm/memory.c:2268
Inline: False
Direct callers:
  - mm/memory.c:vmf_insert_mixed_mkwrite
  - mm/memory.c:vmf_insert_mixed
  - mm/memory.c:vmf_insert_mixed_prot
```
**Symbols:**

```
ffffffff813456b0-ffffffff813457a3: __vm_insert_mixed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
vm_fault_t __vm_insert_mixed(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn, pgprot_t pgprot, bool mkwrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813bda00)
Location: mm/memory.c:2239
Inline: False
Direct callers:
  - mm/memory.c:vmf_insert_mixed_mkwrite
  - mm/memory.c:vmf_insert_mixed
  - mm/memory.c:vmf_insert_mixed_prot
```
**Symbols:**

```
ffffffff813bda00-ffffffff813bdaf3: __vm_insert_mixed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
vm_fault_t __vm_insert_mixed(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn, bool mkwrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813f2700)
Location: mm/memory.c:2272
Inline: False
Direct callers:
  - mm/memory.c:vmf_insert_mixed_mkwrite
  - mm/memory.c:vmf_insert_mixed
```
**Symbols:**

```
ffffffff813f2700-ffffffff813f27fe: __vm_insert_mixed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
vm_fault_t __vm_insert_mixed(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn, bool mkwrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8141d440)
Location: mm/memory.c:2295
Inline: False
Direct callers:
  - mm/memory.c:vmf_insert_mixed_mkwrite
  - mm/memory.c:vmf_insert_mixed
```
**Symbols:**

```
ffffffff8141d440-ffffffff8141d53e: __vm_insert_mixed (STB_LOCAL)
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
vm_fault_t __vm_insert_mixed(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn, bool mkwrite);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102fb7a8)
Location: mm/memory.c:1722
Inline: True
Direct callers:
  - mm/memory.c:vmf_insert_mixed_mkwrite
  - mm/memory.c:vmf_insert_mixed
```
**Symbols:**

```
ffff8000102fb7a8-ffff8000102fb860: __vm_insert_mixed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
vm_fault_t __vm_insert_mixed(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn, bool mkwrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0519fac)
Location: mm/memory.c:1722
Inline: False
Direct callers:
  - mm/memory.c:vmf_insert_mixed_mkwrite
  - mm/memory.c:vmf_insert_mixed
```
**Symbols:**

```
c0519fac-c051a0b0: __vm_insert_mixed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
vm_fault_t __vm_insert_mixed(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn, bool mkwrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003c6800)
Location: mm/memory.c:1722
Inline: False
Direct callers:
  - mm/memory.c:vmf_insert_mixed_mkwrite
  - mm/memory.c:vmf_insert_mixed
```
**Symbols:**

```
c0000000003c6800-c0000000003c6894: __vm_insert_mixed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
vm_fault_t __vm_insert_mixed(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn, bool mkwrite);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe00020ae60)
Location: mm/memory.c:1722
Inline: True
Direct callers:
  - mm/memory.c:vmf_insert_mixed_mkwrite
  - mm/memory.c:vmf_insert_mixed
```
**Symbols:**

```
ffffffe00020ae60-ffffffe00020aeec: __vm_insert_mixed (STB_LOCAL)
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
vm_fault_t __vm_insert_mixed(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn, bool mkwrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125d140)
Location: mm/memory.c:1722
Inline: False
Direct callers:
  - mm/memory.c:vmf_insert_mixed_mkwrite
  - mm/memory.c:vmf_insert_mixed
```
**Symbols:**

```
ffffffff8125d140-ffffffff8125d230: __vm_insert_mixed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
vm_fault_t __vm_insert_mixed(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn, bool mkwrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124f5a0)
Location: mm/memory.c:1722
Inline: False
Direct callers:
  - mm/memory.c:vmf_insert_mixed_mkwrite
  - mm/memory.c:vmf_insert_mixed
```
**Symbols:**

```
ffffffff8124f5a0-ffffffff8124f690: __vm_insert_mixed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
vm_fault_t __vm_insert_mixed(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn, bool mkwrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125aee0)
Location: mm/memory.c:1722
Inline: False
Direct callers:
  - mm/memory.c:vmf_insert_mixed_mkwrite
  - mm/memory.c:vmf_insert_mixed
```
**Symbols:**

```
ffffffff8125aee0-ffffffff8125afd0: __vm_insert_mixed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
vm_fault_t __vm_insert_mixed(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn, bool mkwrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8126a8b0)
Location: mm/memory.c:1722
Inline: False
Direct callers:
  - mm/memory.c:vmf_insert_mixed_mkwrite
  - mm/memory.c:vmf_insert_mixed
```
**Symbols:**

```
ffffffff8126a8b0-ffffffff8126a9a0: __vm_insert_mixed (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<b>Return type changed. </b>
<code>int</code> ➡️ <code>vm_fault_t</code>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>pgprot_t pgprot</code>
</li>
<li>
<b>Param reordered. </b>
<code>vma, addr, pfn, mkwrite</code> ➡️ <code>vma, addr, pfn, pgprot, mkwrite</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>pgprot_t pgprot</code>
</li>
<li>
<b>Param reordered. </b>
<code>vma, addr, pfn, pgprot, mkwrite</code> ➡️ <code>vma, addr, pfn, mkwrite</code>
</li>
</ul>
</details>
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
