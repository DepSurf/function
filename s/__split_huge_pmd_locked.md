# Function: <code>__split_huge_pmd_locked</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81215ed4)
Location: mm/huge_memory.c:1505
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812284f3)
Location: mm/huge_memory.c:1629
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __split_huge_pmd_locked(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int haddr, bool freeze);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81231c00)
Location: mm/huge_memory.c:1951
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd
```
**Symbols:**

```
ffffffff81231c00-ffffffff812322d6: __split_huge_pmd_locked (STB_LOCAL)
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
In mm/huge_memory.c (ffffffff81252875)
Location: mm/huge_memory.c:2070
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
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
In mm/huge_memory.c (ffffffff81276c67)
Location: mm/huge_memory.c:2058
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __split_huge_pmd_locked(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int haddr, bool freeze);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812884d0)
Location: mm/huge_memory.c:2078
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd
```
**Symbols:**

```
ffffffff812884d0-ffffffff81288e7f: __split_huge_pmd_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __split_huge_pmd_locked(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int haddr, bool freeze);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a3120)
Location: mm/huge_memory.c:2135
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd
```
**Symbols:**

```
ffffffff812a3120-ffffffff812a3aea: __split_huge_pmd_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __split_huge_pmd_locked(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int haddr, bool freeze);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812b4620)
Location: mm/huge_memory.c:2140
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd
```
**Symbols:**

```
ffffffff812b4620-ffffffff812b4fea: __split_huge_pmd_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __split_huge_pmd_locked(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int haddr, bool freeze);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812e9bb0)
Location: mm/huge_memory.c:2013
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd
```
**Symbols:**

```
ffffffff812e9bb0-ffffffff812ea51f: __split_huge_pmd_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __split_huge_pmd_locked(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int haddr, bool freeze);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812f4d90)
Location: mm/huge_memory.c:2028
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd
```
**Symbols:**

```
ffffffff812f4d90-ffffffff812f5688: __split_huge_pmd_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __split_huge_pmd_locked(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int haddr, bool freeze);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812fb2d0)
Location: mm/huge_memory.c:2035
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd
```
**Symbols:**

```
ffffffff812fb2d0-ffffffff812fbcc4: __split_huge_pmd_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __split_huge_pmd_locked(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int haddr, bool freeze);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81345100)
Location: mm/huge_memory.c:1958
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd
```
**Symbols:**

```
ffffffff81345100-ffffffff81345ad7: __split_huge_pmd_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __split_huge_pmd_locked(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int haddr, bool freeze);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff813baf30)
Location: mm/huge_memory.c:1984
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd
```
**Symbols:**

```
ffffffff813baf30-ffffffff813bbc21: __split_huge_pmd_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __split_huge_pmd_locked(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int haddr, bool freeze);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/huge_memory.c (0)
Location: mm/huge_memory.c:2078
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd
```
**Symbols:**

```
ffffffff8143d530-ffffffff8143e03a: __split_huge_pmd_locked (STB_LOCAL)
ffffffff82067b04-ffffffff82067b98: __split_huge_pmd_locked.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __split_huge_pmd_locked(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int haddr, bool freeze);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/huge_memory.c (0)
Location: mm/huge_memory.c:2074
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd
```
**Symbols:**

```
ffffffff81472ba0-ffffffff814738bc: __split_huge_pmd_locked (STB_LOCAL)
ffffffff820e7430-ffffffff820e74c4: __split_huge_pmd_locked.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __split_huge_pmd_locked(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int haddr, bool freeze);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/huge_memory.c (0)
Location: mm/huge_memory.c:2409
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd
```
**Symbols:**

```
ffffffff814a1400-ffffffff814a1e73: __split_huge_pmd_locked (STB_LOCAL)
ffffffff821c40c3-ffffffff821c413f: __split_huge_pmd_locked.cold (STB_LOCAL)
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
void __split_huge_pmd_locked(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int haddr, bool freeze);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffff800010355bf0)
Location: mm/huge_memory.c:2140
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd
```
**Symbols:**

```
ffff800010355bf0-ffff8000103562f8: __split_huge_pmd_locked (STB_LOCAL)
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
void __split_huge_pmd_locked(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int haddr, bool freeze);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (c00000000043bef0)
Location: mm/huge_memory.c:2140
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd
```
**Symbols:**

```
c00000000043bef0-c00000000043cb18: __split_huge_pmd_locked (STB_LOCAL)
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
void __split_huge_pmd_locked(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int haddr, bool freeze);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812acc00)
Location: mm/huge_memory.c:2140
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd
```
**Symbols:**

```
ffffffff812acc00-ffffffff812ad5ca: __split_huge_pmd_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __split_huge_pmd_locked(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int haddr, bool freeze);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8129dcf0)
Location: mm/huge_memory.c:2140
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd
```
**Symbols:**

```
ffffffff8129dcf0-ffffffff8129e54c: __split_huge_pmd_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __split_huge_pmd_locked(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int haddr, bool freeze);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812aaa10)
Location: mm/huge_memory.c:2140
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd
```
**Symbols:**

```
ffffffff812aaa10-ffffffff812ab3da: __split_huge_pmd_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __split_huge_pmd_locked(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int haddr, bool freeze);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812bad60)
Location: mm/huge_memory.c:2140
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd
```
**Symbols:**

```
ffffffff812bad60-ffffffff812bb72a: __split_huge_pmd_locked (STB_LOCAL)
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
