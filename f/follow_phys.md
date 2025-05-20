# Function: <code>follow_phys</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int follow_phys(struct vm_area_struct *vma, long unsigned int address, unsigned int flags, long unsigned int *prot, resource_size_t *phys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811c1cf0)
Location: mm/memory.c:3604
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:track_pfn_copy
  - arch/x86/mm/pat.c:untrack_pfn
  - mm/memory.c:generic_access_phys
```
**Symbols:**

```
ffffffff811c1cf0-ffffffff811c1db6: follow_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int follow_phys(struct vm_area_struct *vma, long unsigned int address, unsigned int flags, long unsigned int *prot, resource_size_t *phys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811dd820)
Location: mm/memory.c:3799
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:untrack_pfn
  - arch/x86/mm/pat.c:track_pfn_copy
  - mm/memory.c:generic_access_phys
```
**Symbols:**

```
ffffffff811dd820-ffffffff811dd8e6: follow_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int follow_phys(struct vm_area_struct *vma, long unsigned int address, unsigned int flags, long unsigned int *prot, resource_size_t *phys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811ed350)
Location: mm/memory.c:3877
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:untrack_pfn
  - arch/x86/mm/pat.c:track_pfn_copy
  - mm/memory.c:generic_access_phys
```
**Symbols:**

```
ffffffff811ed350-ffffffff811ed418: follow_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int follow_phys(struct vm_area_struct *vma, long unsigned int address, unsigned int flags, long unsigned int *prot, resource_size_t *phys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f8360)
Location: mm/memory.c:4167
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:untrack_pfn
  - arch/x86/mm/pat.c:track_pfn_copy
  - mm/memory.c:generic_access_phys
```
**Symbols:**

```
ffffffff811f8360-ffffffff811f842b: follow_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int follow_phys(struct vm_area_struct *vma, long unsigned int address, unsigned int flags, long unsigned int *prot, resource_size_t *phys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81210510)
Location: mm/memory.c:4345
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:untrack_pfn
  - arch/x86/mm/pat.c:track_pfn_copy
  - mm/memory.c:generic_access_phys
```
**Symbols:**

```
ffffffff81210510-ffffffff812105ef: follow_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int follow_phys(struct vm_area_struct *vma, long unsigned int address, unsigned int flags, long unsigned int *prot, resource_size_t *phys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81230f00)
Location: mm/memory.c:4390
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:untrack_pfn
  - arch/x86/mm/pat.c:track_pfn_copy
  - mm/memory.c:generic_access_phys
```
**Symbols:**

```
ffffffff81230f00-ffffffff81230feb: follow_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int follow_phys(struct vm_area_struct *vma, long unsigned int address, unsigned int flags, long unsigned int *prot, resource_size_t *phys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812446d0)
Location: mm/memory.c:4180
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:untrack_pfn
  - arch/x86/mm/pat.c:track_pfn_copy
  - mm/memory.c:generic_access_phys
```
**Symbols:**

```
ffffffff812446d0-ffffffff812447b7: follow_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int follow_phys(struct vm_area_struct *vma, long unsigned int address, unsigned int flags, long unsigned int *prot, resource_size_t *phys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81256690)
Location: mm/memory.c:4231
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:untrack_pfn
  - arch/x86/mm/pat.c:track_pfn_copy
  - mm/memory.c:generic_access_phys
```
**Symbols:**

```
ffffffff81256690-ffffffff8125677b: follow_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int follow_phys(struct vm_area_struct *vma, long unsigned int address, unsigned int flags, long unsigned int *prot, resource_size_t *phys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81264c20)
Location: mm/memory.c:4256
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:untrack_pfn
  - arch/x86/mm/pat.c:track_pfn_copy
  - mm/memory.c:generic_access_phys
```
**Symbols:**

```
ffffffff81264c20-ffffffff81264d0b: follow_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int follow_phys(struct vm_area_struct *vma, long unsigned int address, unsigned int flags, long unsigned int *prot, resource_size_t *phys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81294ff0)
Location: mm/memory.c:4621
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:untrack_pfn
  - arch/x86/mm/pat/memtype.c:track_pfn_copy
  - mm/memory.c:generic_access_phys
```
**Symbols:**

```
ffffffff81294ff0-ffffffff812950da: follow_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int follow_phys(struct vm_area_struct *vma, long unsigned int address, unsigned int flags, long unsigned int *prot, resource_size_t *phys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129fe60)
Location: mm/memory.c:4849
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:untrack_pfn
  - arch/x86/mm/pat/memtype.c:track_pfn_copy
  - mm/memory.c:generic_access_phys
```
**Symbols:**

```
ffffffff8129fe60-ffffffff8129ff4a: follow_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int follow_phys(struct vm_area_struct *vma, long unsigned int address, unsigned int flags, long unsigned int *prot, resource_size_t *phys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a5880)
Location: mm/memory.c:4876
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:untrack_pfn
  - arch/x86/mm/pat/memtype.c:track_pfn_copy
```
**Symbols:**

```
ffffffff812a5880-ffffffff812a596a: follow_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int follow_phys(struct vm_area_struct *vma, long unsigned int address, unsigned int flags, long unsigned int *prot, resource_size_t *phys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812e6d70)
Location: mm/memory.c:5022
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:untrack_pfn
  - arch/x86/mm/pat/memtype.c:track_pfn_copy
```
**Symbols:**

```
ffffffff812e6d70-ffffffff812e6e5a: follow_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int follow_phys(struct vm_area_struct *vma, long unsigned int address, unsigned int flags, long unsigned int *prot, resource_size_t *phys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81347ee0)
Location: mm/memory.c:5329
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:untrack_pfn
  - arch/x86/mm/pat/memtype.c:track_pfn_copy
```
**Symbols:**

```
ffffffff81347ee0-ffffffff81347fe3: follow_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int follow_phys(struct vm_area_struct *vma, long unsigned int address, unsigned int flags, long unsigned int *prot, resource_size_t *phys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813c0370)
Location: mm/memory.c:5409
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:untrack_pfn
  - arch/x86/mm/pat/memtype.c:track_pfn_copy
```
**Symbols:**

```
ffffffff813c0370-ffffffff813c0473: follow_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int follow_phys(struct vm_area_struct *vma, long unsigned int address, unsigned int flags, long unsigned int *prot, resource_size_t *phys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813f5060)
Location: mm/memory.c:5600
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:untrack_pfn
  - arch/x86/mm/pat/memtype.c:track_pfn_copy
```
**Symbols:**

```
ffffffff813f5060-ffffffff813f5164: follow_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int follow_phys(struct vm_area_struct *vma, long unsigned int address, unsigned int flags, long unsigned int *prot, resource_size_t *phys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8141f240)
Location: mm/memory.c:5826
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:untrack_pfn
  - arch/x86/mm/pat/memtype.c:track_pfn_copy
```
**Symbols:**

```
ffffffff8141f240-ffffffff8141f35a: follow_phys (STB_GLOBAL)
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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int follow_phys(struct vm_area_struct *vma, long unsigned int address, unsigned int flags, long unsigned int *prot, resource_size_t *phys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003c68e0)
Location: mm/memory.c:4256
Inline: False
Direct callers:
  - mm/memory.c:generic_access_phys
```
**Symbols:**

```
c0000000003c68e0-c0000000003c6a68: follow_phys (STB_GLOBAL)
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
int follow_phys(struct vm_area_struct *vma, long unsigned int address, unsigned int flags, long unsigned int *prot, resource_size_t *phys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125d270)
Location: mm/memory.c:4256
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:untrack_pfn
  - arch/x86/mm/pat.c:track_pfn_copy
  - mm/memory.c:generic_access_phys
```
**Symbols:**

```
ffffffff8125d270-ffffffff8125d35b: follow_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int follow_phys(struct vm_area_struct *vma, long unsigned int address, unsigned int flags, long unsigned int *prot, resource_size_t *phys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124f6d0)
Location: mm/memory.c:4256
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:untrack_pfn
  - arch/x86/mm/pat.c:track_pfn_copy
  - mm/memory.c:generic_access_phys
```
**Symbols:**

```
ffffffff8124f6d0-ffffffff8124f7b0: follow_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int follow_phys(struct vm_area_struct *vma, long unsigned int address, unsigned int flags, long unsigned int *prot, resource_size_t *phys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125b010)
Location: mm/memory.c:4256
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:untrack_pfn
  - arch/x86/mm/pat.c:track_pfn_copy
  - mm/memory.c:generic_access_phys
```
**Symbols:**

```
ffffffff8125b010-ffffffff8125b0fb: follow_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int follow_phys(struct vm_area_struct *vma, long unsigned int address, unsigned int flags, long unsigned int *prot, resource_size_t *phys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8126a9e0)
Location: mm/memory.c:4256
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:untrack_pfn
  - arch/x86/mm/pat.c:track_pfn_copy
  - mm/memory.c:generic_access_phys
```
**Symbols:**

```
ffffffff8126a9e0-ffffffff8126aacd: follow_phys (STB_GLOBAL)
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
