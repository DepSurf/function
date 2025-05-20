# Function: <code>pudp_huge_clear_flush</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
pud_t pudp_huge_clear_flush(struct vm_area_struct *vma, long unsigned int address, pud_t *pudp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81202c10)
Location: mm/pgtable-generic.c:134
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pud
```
**Symbols:**

```
ffffffff81202c10-ffffffff81202c39: pudp_huge_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
pud_t pudp_huge_clear_flush(struct vm_area_struct *vma, long unsigned int address, pud_t *pudp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff8121b970)
Location: mm/pgtable-generic.c:136
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pud
```
**Symbols:**

```
ffffffff8121b970-ffffffff8121b999: pudp_huge_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
pud_t pudp_huge_clear_flush(struct vm_area_struct *vma, long unsigned int address, pud_t *pudp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff8123d750)
Location: mm/pgtable-generic.c:136
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pud
```
**Symbols:**

```
ffffffff8123d750-ffffffff8123d779: pudp_huge_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
pud_t pudp_huge_clear_flush(struct vm_area_struct *vma, long unsigned int address, pud_t *pudp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81251cd0)
Location: mm/pgtable-generic.c:137
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pud
```
**Symbols:**

```
ffffffff81251cd0-ffffffff81251d23: pudp_huge_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
pud_t pudp_huge_clear_flush(struct vm_area_struct *vma, long unsigned int address, pud_t *pudp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81263fb0)
Location: mm/pgtable-generic.c:137
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pud
```
**Symbols:**

```
ffffffff81263fb0-ffffffff81264006: pudp_huge_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
pud_t pudp_huge_clear_flush(struct vm_area_struct *vma, long unsigned int address, pud_t *pudp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81272820)
Location: mm/pgtable-generic.c:137
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pud
```
**Symbols:**

```
ffffffff81272820-ffffffff81272876: pudp_huge_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
pud_t pudp_huge_clear_flush(struct vm_area_struct *vma, long unsigned int address, pud_t *pudp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff812a35e0)
Location: mm/pgtable-generic.c:146
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pud
```
**Symbols:**

```
ffffffff812a35e0-ffffffff812a3638: pudp_huge_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
pud_t pudp_huge_clear_flush(struct vm_area_struct *vma, long unsigned int address, pud_t *pudp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff812aeec0)
Location: mm/pgtable-generic.c:146
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pud
```
**Symbols:**

```
ffffffff812aeec0-ffffffff812aef18: pudp_huge_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
pud_t pudp_huge_clear_flush(struct vm_area_struct *vma, long unsigned int address, pud_t *pudp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff812b43f0)
Location: mm/pgtable-generic.c:146
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pud
```
**Symbols:**

```
ffffffff812b43f0-ffffffff812b444b: pudp_huge_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
pud_t pudp_huge_clear_flush(struct vm_area_struct *vma, long unsigned int address, pud_t *pudp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff812f5fd0)
Location: mm/pgtable-generic.c:146
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pud
```
**Symbols:**

```
ffffffff812f5fd0-ffffffff812f602b: pudp_huge_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
pud_t pudp_huge_clear_flush(struct vm_area_struct *vma, long unsigned int address, pud_t *pudp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81359f90)
Location: mm/pgtable-generic.c:147
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pud
```
**Symbols:**

```
ffffffff81359f90-ffffffff81359ff8: pudp_huge_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
pud_t pudp_huge_clear_flush(struct vm_area_struct *vma, long unsigned int address, pud_t *pudp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff813d49e0)
Location: mm/pgtable-generic.c:147
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pud
```
**Symbols:**

```
ffffffff813d49e0-ffffffff813d4a45: pudp_huge_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
pud_t pudp_huge_clear_flush(struct vm_area_struct *vma, long unsigned int address, pud_t *pudp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff814093b0)
Location: mm/pgtable-generic.c:149
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pud
```
**Symbols:**

```
ffffffff814093b0-ffffffff8140941b: pudp_huge_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
pud_t pudp_huge_clear_flush(struct vm_area_struct *vma, long unsigned int address, pud_t *pudp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81435ba0)
Location: mm/pgtable-generic.c:150
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pud
```
**Symbols:**

```
ffffffff81435ba0-ffffffff81435c0b: pudp_huge_clear_flush (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
pud_t pudp_huge_clear_flush(struct vm_area_struct *vma, long unsigned int address, pud_t *pudp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff8126ae70)
Location: mm/pgtable-generic.c:137
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pud
```
**Symbols:**

```
ffffffff8126ae70-ffffffff8126aec6: pudp_huge_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
pud_t pudp_huge_clear_flush(struct vm_area_struct *vma, long unsigned int address, pud_t *pudp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff8125cea0)
Location: mm/pgtable-generic.c:137
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pud
```
**Symbols:**

```
ffffffff8125cea0-ffffffff8125cef6: pudp_huge_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
pud_t pudp_huge_clear_flush(struct vm_area_struct *vma, long unsigned int address, pud_t *pudp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81268c10)
Location: mm/pgtable-generic.c:137
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pud
```
**Symbols:**

```
ffffffff81268c10-ffffffff81268c66: pudp_huge_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
pud_t pudp_huge_clear_flush(struct vm_area_struct *vma, long unsigned int address, pud_t *pudp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff812785a0)
Location: mm/pgtable-generic.c:137
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pud
```
**Symbols:**

```
ffffffff812785a0-ffffffff812785f6: pudp_huge_clear_flush (STB_GLOBAL)
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
