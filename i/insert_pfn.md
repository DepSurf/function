# Function: <code>insert_pfn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory.c (ffffffff811c1ae0)
Location: mm/memory.c:1519
Inline: True
Direct callers:
  - mm/memory.c:vm_insert_pfn
```
**Symbols:**

```
ffffffff811c1ae0-ffffffff811c1ba4: insert_pfn.isra.66 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory.c (ffffffff811dd5e0)
Location: mm/memory.c:1552
Inline: True
Direct callers:
  - mm/memory.c:vm_insert_pfn_prot
```
**Symbols:**

```
ffffffff811dd5e0-ffffffff811dd6cc: insert_pfn.isra.61 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory.c (ffffffff811ed0d0)
Location: mm/memory.c:1548
Inline: True
Direct callers:
  - mm/memory.c:vm_insert_pfn_prot
```
**Symbols:**

```
ffffffff811ed0d0-ffffffff811ed1bc: insert_pfn.isra.66 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int insert_pfn(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn, pgprot_t prot, bool mkwrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f7ff0)
Location: mm/memory.c:1678
Inline: False
Direct callers:
  - mm/memory.c:vm_insert_pfn_prot
```
**Symbols:**

```
ffffffff811f7ff0-ffffffff811f816c: insert_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int insert_pfn(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn, pgprot_t prot, bool mkwrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81210160)
Location: mm/memory.c:1781
Inline: False
Direct callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:vm_insert_pfn_prot
```
**Symbols:**

```
ffffffff81210160-ffffffff812102ea: insert_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int insert_pfn(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn, pgprot_t prot, bool mkwrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8122f840)
Location: mm/memory.c:1792
Inline: False
Direct callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:vm_insert_pfn_prot
```
**Symbols:**

```
ffffffff8122f840-ffffffff8122fa2b: insert_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
vm_fault_t insert_pfn(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn, pgprot_t prot, bool mkwrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81244230)
Location: mm/memory.c:1524
Inline: False
Direct callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:vmf_insert_pfn_prot
```
**Symbols:**

```
ffffffff81244230-ffffffff81244462: insert_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
vm_fault_t insert_pfn(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn, pgprot_t prot, bool mkwrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812561e0)
Location: mm/memory.c:1577
Inline: False
Direct callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:vmf_insert_pfn_prot
```
**Symbols:**

```
ffffffff812561e0-ffffffff81256407: insert_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
vm_fault_t insert_pfn(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn, pgprot_t prot, bool mkwrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81264770)
Location: mm/memory.c:1582
Inline: False
Direct callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:vmf_insert_pfn_prot
```
**Symbols:**

```
ffffffff81264770-ffffffff81264997: insert_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
vm_fault_t insert_pfn(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn, pgprot_t prot, bool mkwrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812929e0)
Location: mm/memory.c:1745
Inline: False
Direct callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:vmf_insert_pfn_prot
```
**Symbols:**

```
ffffffff812929e0-ffffffff81292bfb: insert_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
vm_fault_t insert_pfn(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn, pgprot_t prot, bool mkwrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129d310)
Location: mm/memory.c:1919
Inline: False
Direct callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:vmf_insert_pfn_prot
```
**Symbols:**

```
ffffffff8129d310-ffffffff8129d512: insert_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
vm_fault_t insert_pfn(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn, pgprot_t prot, bool mkwrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a29d0)
Location: mm/memory.c:1937
Inline: False
Direct callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:vmf_insert_pfn_prot
```
**Symbols:**

```
ffffffff812a29d0-ffffffff812a2b44: insert_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
vm_fault_t insert_pfn(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn, pgprot_t prot, bool mkwrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812e5e20)
Location: mm/memory.c:2032
Inline: False
Direct callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:vmf_insert_pfn_prot
```
**Symbols:**

```
ffffffff812e5e20-ffffffff812e5f92: insert_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
vm_fault_t insert_pfn(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn, pgprot_t prot, bool mkwrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81345400)
Location: mm/memory.c:2125
Inline: False
Direct callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:vmf_insert_pfn_prot
```
**Symbols:**

```
ffffffff81345400-ffffffff81345586: insert_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
vm_fault_t insert_pfn(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn, pgprot_t prot, bool mkwrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813bd690)
Location: mm/memory.c:2096
Inline: False
Direct callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:vmf_insert_pfn_prot
```
**Symbols:**

```
ffffffff813bd690-ffffffff813bd816: insert_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
vm_fault_t insert_pfn(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn, pgprot_t prot, bool mkwrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813f2370)
Location: mm/memory.c:2116
Inline: False
Direct callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:vmf_insert_pfn_prot
```
**Symbols:**

```
ffffffff813f2370-ffffffff813f251b: insert_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
vm_fault_t insert_pfn(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn, pgprot_t prot, bool mkwrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8141d000)
Location: mm/memory.c:2139
Inline: False
Direct callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:vmf_insert_pfn_prot
```
**Symbols:**

```
ffffffff8141d000-ffffffff8141d211: insert_pfn (STB_LOCAL)
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
vm_fault_t insert_pfn(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn, pgprot_t prot, bool mkwrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102fb508)
Location: mm/memory.c:1582
Inline: False
Direct callers:
  - mm/memory.c:vmf_insert_pfn_prot
```
**Symbols:**

```
ffff8000102fb508-ffff8000102fb69c: insert_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
vm_fault_t insert_pfn(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn, pgprot_t prot, bool mkwrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0519d28)
Location: mm/memory.c:1582
Inline: False
Direct callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:vmf_insert_pfn_prot
```
**Symbols:**

```
c0519d28-c0519ebc: insert_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
vm_fault_t insert_pfn(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn, pgprot_t prot, bool mkwrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003c63d0)
Location: mm/memory.c:1582
Inline: False
Direct callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:vmf_insert_pfn_prot
```
**Symbols:**

```
c0000000003c63d0-c0000000003c66a8: insert_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
vm_fault_t insert_pfn(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn, pgprot_t prot, bool mkwrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe00020ac22)
Location: mm/memory.c:1582
Inline: False
Direct callers:
  - mm/memory.c:vmf_insert_pfn_prot
```
**Symbols:**

```
ffffffe00020ac22-ffffffe00020ad4a: insert_pfn (STB_LOCAL)
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
vm_fault_t insert_pfn(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn, pgprot_t prot, bool mkwrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125cdc0)
Location: mm/memory.c:1582
Inline: False
Direct callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:vmf_insert_pfn_prot
```
**Symbols:**

```
ffffffff8125cdc0-ffffffff8125cfe7: insert_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
vm_fault_t insert_pfn(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn, pgprot_t prot, bool mkwrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124f280)
Location: mm/memory.c:1582
Inline: False
Direct callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:vmf_insert_pfn_prot
```
**Symbols:**

```
ffffffff8124f280-ffffffff8124f44b: insert_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
vm_fault_t insert_pfn(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn, pgprot_t prot, bool mkwrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125ab60)
Location: mm/memory.c:1582
Inline: False
Direct callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:vmf_insert_pfn_prot
```
**Symbols:**

```
ffffffff8125ab60-ffffffff8125ad87: insert_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
vm_fault_t insert_pfn(struct vm_area_struct *vma, long unsigned int addr, pfn_t pfn, pgprot_t prot, bool mkwrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8126a530)
Location: mm/memory.c:1582
Inline: False
Direct callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:vmf_insert_pfn_prot
```
**Symbols:**

```
ffffffff8126a530-ffffffff8126a755: insert_pfn (STB_LOCAL)
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
