# Function: <code>insert_pfn_pud</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81231510)
Location: mm/huge_memory.c:798
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8124f6d8)
Location: mm/huge_memory.c:798
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8127372c)
Location: mm/huge_memory.c:795
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81287ab9)
Location: mm/huge_memory.c:814
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a219b)
Location: mm/huge_memory.c:852
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812b354b)
Location: mm/huge_memory.c:858
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void insert_pfn_pud(struct vm_area_struct *vma, long unsigned int addr, pud_t *pud, pfn_t pfn, pgprot_t prot, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812e8e60)
Location: mm/huge_memory.c:880
Inline: False
Direct callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud_prot
```
**Symbols:**

```
ffffffff812e8e60-ffffffff812e8ffc: insert_pfn_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void insert_pfn_pud(struct vm_area_struct *vma, long unsigned int addr, pud_t *pud, pfn_t pfn, pgprot_t prot, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812f42d0)
Location: mm/huge_memory.c:872
Inline: False
Direct callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud_prot
```
**Symbols:**

```
ffffffff812f42d0-ffffffff812f446c: insert_pfn_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void insert_pfn_pud(struct vm_area_struct *vma, long unsigned int addr, pud_t *pud, pfn_t pfn, pgprot_t prot, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812fa510)
Location: mm/huge_memory.c:888
Inline: False
Direct callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud_prot
```
**Symbols:**

```
ffffffff812fa510-ffffffff812fa6be: insert_pfn_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void insert_pfn_pud(struct vm_area_struct *vma, long unsigned int addr, pud_t *pud, pfn_t pfn, pgprot_t prot, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81344370)
Location: mm/huge_memory.c:888
Inline: False
Direct callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud_prot
```
**Symbols:**

```
ffffffff81344370-ffffffff8134451e: insert_pfn_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void insert_pfn_pud(struct vm_area_struct *vma, long unsigned int addr, pud_t *pud, pfn_t pfn, pgprot_t prot, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff813b9870)
Location: mm/huge_memory.c:882
Inline: False
Direct callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud_prot
```
**Symbols:**

```
ffffffff813b9870-ffffffff813b9a25: insert_pfn_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void insert_pfn_pud(struct vm_area_struct *vma, long unsigned int addr, pud_t *pud, pfn_t pfn, pgprot_t prot, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8143bd50)
Location: mm/huge_memory.c:942
Inline: False
Direct callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud_prot
```
**Symbols:**

```
ffffffff8143bd50-ffffffff8143bf0c: insert_pfn_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void insert_pfn_pud(struct vm_area_struct *vma, long unsigned int addr, pud_t *pud, pfn_t pfn, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81471860)
Location: mm/huge_memory.c:939
Inline: False
Direct callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
**Symbols:**

```
ffffffff81471860-ffffffff81471a22: insert_pfn_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void insert_pfn_pud(struct vm_area_struct *vma, long unsigned int addr, pud_t *pud, pfn_t pfn, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff814a1010)
Location: mm/huge_memory.c:1154
Inline: False
Direct callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
**Symbols:**

```
ffffffff814a1010-ffffffff814a1222: insert_pfn_pud (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812abb2b)
Location: mm/huge_memory.c:858
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8129d429)
Location: mm/huge_memory.c:858
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a993b)
Location: mm/huge_memory.c:858
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812b978e)
Location: mm/huge_memory.c:858
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<code>pgprot_t prot</code>
</li>
<li>
<b>Param reordered. </b>
<code>vma, addr, pud, pfn, prot, write</code> ➡️ <code>vma, addr, pud, pfn, write</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
