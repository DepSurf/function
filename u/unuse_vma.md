# Function: <code>unuse_vma</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff811d4084)
Location: mm/swapfile.c:1271
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff811f1ec1)
Location: mm/swapfile.c:1261
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
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
In mm/swapfile.c (ffffffff812028b1)
Location: mm/swapfile.c:1282
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8120d9a3)
Location: mm/swapfile.c:1714
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
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
In mm/swapfile.c (ffffffff81228b53)
Location: mm/swapfile.c:1926
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int unuse_vma(struct vm_area_struct *vma, swp_entry_t entry, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81249e50)
Location: mm/swapfile.c:1926
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_mm
```
**Symbols:**

```
ffffffff81249e50-ffffffff8124a5ab: unuse_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int unuse_vma(struct vm_area_struct *vma, swp_entry_t entry, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8125e490)
Location: mm/swapfile.c:1898
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_mm
```
**Symbols:**

```
ffffffff8125e490-ffffffff8125ebf4: unuse_vma (STB_LOCAL)
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
In mm/swapfile.c (ffffffff8127b796)
Location: mm/swapfile.c:2044
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
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
In mm/swapfile.c (ffffffff8128b276)
Location: mm/swapfile.c:2044
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int unuse_vma(struct vm_area_struct *vma, unsigned int type, bool frontswap, long unsigned int *fs_pages_to_unuse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812bdf50)
Location: mm/swapfile.c:2074
Inline: False
Direct callers:
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
ffffffff812bdf50-ffffffff812be086: unuse_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int unuse_vma(struct vm_area_struct *vma, unsigned int type, bool frontswap, long unsigned int *fs_pages_to_unuse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812c9a70)
Location: mm/swapfile.c:2090
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_mm
```
**Symbols:**

```
ffffffff812c9a70-ffffffff812c9ba6: unuse_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int unuse_vma(struct vm_area_struct *vma, unsigned int type, bool frontswap, long unsigned int *fs_pages_to_unuse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812d02c0)
Location: mm/swapfile.c:2091
Inline: False
Direct callers:
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
ffffffff812d02c0-ffffffff812d06f2: unuse_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int unuse_vma(struct vm_area_struct *vma, unsigned int type, bool frontswap, long unsigned int *fs_pages_to_unuse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:2078
Inline: False
Direct callers:
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
ffffffff813157e0-ffffffff81315c3c: unuse_vma (STB_LOCAL)
ffffffff81cbebeb-ffffffff81cbec45: unuse_vma.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int unuse_vma(struct vm_area_struct *vma, unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:1969
Inline: False
Direct callers:
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
ffffffff81380db0-ffffffff8138122e: unuse_vma (STB_LOCAL)
ffffffff81e70d95-ffffffff81e70dfb: unuse_vma.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int unuse_vma(struct vm_area_struct *vma, unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:1969
Inline: False
Direct callers:
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
ffffffff813ff600-ffffffff813ffa4d: unuse_vma (STB_LOCAL)
ffffffff82065c83-ffffffff82065ce9: unuse_vma.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int unuse_vma(struct vm_area_struct *vma, unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:1960
Inline: False
Direct callers:
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
ffffffff81432670-ffffffff814328d8: unuse_vma (STB_LOCAL)
ffffffff820e5415-ffffffff820e54b1: unuse_vma.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int unuse_vma(struct vm_area_struct *vma, unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:1968
Inline: False
Direct callers:
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
ffffffff8146ba90-ffffffff8146bcf8: unuse_vma (STB_LOCAL)
ffffffff821c25be-ffffffff821c265a: unuse_vma.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffff800010326658)
Location: mm/swapfile.c:2044
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c053d50c)
Location: mm/swapfile.c:2044
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c0000000003fcd2c)
Location: mm/swapfile.c:2044
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffe0002267f0)
Location: mm/swapfile.c:2044
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
</details>
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
In mm/swapfile.c (ffffffff81283856)
Location: mm/swapfile.c:2044
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
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
In mm/swapfile.c (ffffffff81275710)
Location: mm/swapfile.c:2044
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
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
In mm/swapfile.c (ffffffff81281666)
Location: mm/swapfile.c:2044
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
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
In mm/swapfile.c (ffffffff812913a1)
Location: mm/swapfile.c:2044
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool frontswap</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int *fs_pages_to_unuse</code>
</li>
</ul>
</details>
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
