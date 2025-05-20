# Function: <code>touch_pmd</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void touch_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81213930)
Location: mm/huge_memory.c:686
Inline: False
Direct callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
**Symbols:**

```
ffffffff81213930-ffffffff81213975: touch_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void touch_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81225cc0)
Location: mm/huge_memory.c:758
Inline: False
Direct callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
**Symbols:**

```
ffffffff81225cc0-ffffffff81225d05: touch_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void touch_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81231600)
Location: mm/huge_memory.c:844
Inline: False
Direct callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
**Symbols:**

```
ffffffff81231600-ffffffff81231645: touch_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void touch_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8124f2c0)
Location: mm/huge_memory.c:844
Inline: False
Direct callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
**Symbols:**

```
ffffffff8124f2c0-ffffffff8124f2f4: touch_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void touch_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81273090)
Location: mm/huge_memory.c:841
Inline: False
Direct callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
**Symbols:**

```
ffffffff81273090-ffffffff812730c4: touch_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void touch_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81287600)
Location: mm/huge_memory.c:860
Inline: False
Direct callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
**Symbols:**

```
ffffffff81287600-ffffffff81287634: touch_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void touch_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a1bd0)
Location: mm/huge_memory.c:916
Inline: False
Direct callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
**Symbols:**

```
ffffffff812a1bd0-ffffffff812a1c03: touch_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void touch_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812b2f80)
Location: mm/huge_memory.c:922
Inline: False
Direct callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
**Symbols:**

```
ffffffff812b2f80-ffffffff812b2fb3: touch_pmd (STB_LOCAL)
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
In mm/huge_memory.c (ffffffff812eb805)
Location: mm/huge_memory.c:957
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
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
In mm/huge_memory.c (ffffffff812f68bd)
Location: mm/huge_memory.c:949
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
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
In mm/huge_memory.c (ffffffff812fcc61)
Location: mm/huge_memory.c:965
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
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
In mm/huge_memory.c (ffffffff81346ae1)
Location: mm/huge_memory.c:965
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
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
In mm/huge_memory.c (ffffffff813bcda0)
Location: mm/huge_memory.c:959
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
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
In mm/huge_memory.c (ffffffff8143f3e8)
Location: mm/huge_memory.c:1019
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:follow_devmap_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81474b8e)
Location: mm/huge_memory.c:1014
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:follow_devmap_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void touch_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, bool write);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff814a3e1f)
Location: mm/huge_memory.c:1229
Inline: True
Inline callers:
  - mm/huge_memory.c:huge_pmd_set_accessed
Direct callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
**Symbols:**

```
ffffffff814a0a10-ffffffff814a0a80: touch_pmd (STB_LOCAL)
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
void touch_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffff800010353f10)
Location: mm/huge_memory.c:922
Inline: False
Direct callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
**Symbols:**

```
ffff800010353f10-ffff800010353f84: touch_pmd (STB_LOCAL)
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
void touch_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (c00000000043ac30)
Location: mm/huge_memory.c:922
Inline: False
Direct callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
**Symbols:**

```
c00000000043ac30-c00000000043ad40: touch_pmd (STB_LOCAL)
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
void touch_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812ab560)
Location: mm/huge_memory.c:922
Inline: False
Direct callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
**Symbols:**

```
ffffffff812ab560-ffffffff812ab593: touch_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void touch_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8129ce60)
Location: mm/huge_memory.c:922
Inline: False
Direct callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
**Symbols:**

```
ffffffff8129ce60-ffffffff8129ce93: touch_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void touch_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a9370)
Location: mm/huge_memory.c:922
Inline: False
Direct callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
**Symbols:**

```
ffffffff812a9370-ffffffff812a93a3: touch_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void touch_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812b9690)
Location: mm/huge_memory.c:922
Inline: False
Direct callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
**Symbols:**

```
ffffffff812b9690-ffffffff812b96c3: touch_pmd (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int flags</code>
</li>
</ul>
</details>
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
