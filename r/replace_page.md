# Function: <code>replace_page</code>

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
In mm/ksm.c (ffffffff811e55f9)
Location: mm/ksm.c:930
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_with_ksm_page
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
In mm/ksm.c (ffffffff812040b2)
Location: mm/ksm.c:918
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_with_ksm_page
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
In mm/ksm.c (ffffffff8121601e)
Location: mm/ksm.c:936
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
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
In mm/ksm.c (ffffffff81221813)
Location: mm/ksm.c:1094
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
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
In mm/ksm.c (ffffffff8123cb24)
Location: mm/ksm.c:1099
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
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
In mm/ksm.c (ffffffff81260402)
Location: mm/ksm.c:1122
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
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
In mm/ksm.c (ffffffff81274b45)
Location: mm/ksm.c:1122
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int replace_page(struct vm_area_struct *vma, struct page *page, struct page *kpage, pte_t orig_pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8128f610)
Location: mm/ksm.c:1137
Inline: False
Direct callers:
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff8128f610-ffffffff8128f9c6: replace_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int replace_page(struct vm_area_struct *vma, struct page *page, struct page *kpage, pte_t orig_pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8129f390)
Location: mm/ksm.c:1119
Inline: False
Direct callers:
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff8129f390-ffffffff8129f75c: replace_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int replace_page(struct vm_area_struct *vma, struct page *page, struct page *kpage, pte_t orig_pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812d39e0)
Location: mm/ksm.c:1119
Inline: False
Direct callers:
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff812d39e0-ffffffff812d3dc3: replace_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int replace_page(struct vm_area_struct *vma, struct page *page, struct page *kpage, pte_t orig_pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812df3e0)
Location: mm/ksm.c:1120
Inline: False
Direct callers:
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff812df3e0-ffffffff812df7bf: replace_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int replace_page(struct vm_area_struct *vma, struct page *page, struct page *kpage, pte_t orig_pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812e7d00)
Location: mm/ksm.c:1118
Inline: False
Direct callers:
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff812e7d00-ffffffff812e80d4: replace_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int replace_page(struct vm_area_struct *vma, struct page *page, struct page *kpage, pte_t orig_pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8132fc30)
Location: mm/ksm.c:1114
Inline: False
Direct callers:
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff8132fc30-ffffffff8133000b: replace_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int replace_page(struct vm_area_struct *vma, struct page *page, struct page *kpage, pte_t orig_pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8139fff0)
Location: mm/ksm.c:1132
Inline: False
Direct callers:
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff8139fff0-ffffffff813a0461: replace_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int replace_page(struct vm_area_struct *vma, struct page *page, struct page *kpage, pte_t orig_pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8141ee80)
Location: mm/ksm.c:1136
Inline: False
Direct callers:
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff8141ee80-ffffffff8141f348: replace_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int replace_page(struct vm_area_struct *vma, struct page *page, struct page *kpage, pte_t orig_pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81453a90)
Location: mm/ksm.c:1179
Inline: False
Direct callers:
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff81453a90-ffffffff81453ee2: replace_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int replace_page(struct vm_area_struct *vma, struct page *page, struct page *kpage, pte_t orig_pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8148e2c0)
Location: mm/ksm.c:1370
Inline: False
Direct callers:
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff8148e2c0-ffffffff8148e7a4: replace_page (STB_LOCAL)
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
In mm/ksm.c (ffff80001033eb8c)
Location: mm/ksm.c:1119
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int replace_page(struct vm_area_struct *vma, struct page *page, struct page *kpage, pte_t orig_pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (c0544e50)
Location: mm/ksm.c:1119
Inline: False
Direct callers:
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
c0544e50-c05451e8: replace_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int replace_page(struct vm_area_struct *vma, struct page *page, struct page *kpage, pte_t orig_pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (c00000000041ab60)
Location: mm/ksm.c:1119
Inline: False
Direct callers:
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
c00000000041ab60-c00000000041b080: replace_page (STB_LOCAL)
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
In mm/ksm.c (ffffffe00023487c)
Location: mm/ksm.c:1119
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
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
int replace_page(struct vm_area_struct *vma, struct page *page, struct page *kpage, pte_t orig_pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81297970)
Location: mm/ksm.c:1119
Inline: False
Direct callers:
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff81297970-ffffffff81297d3c: replace_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int replace_page(struct vm_area_struct *vma, struct page *page, struct page *kpage, pte_t orig_pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81289560)
Location: mm/ksm.c:1119
Inline: False
Direct callers:
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff81289560-ffffffff812898f2: replace_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int replace_page(struct vm_area_struct *vma, struct page *page, struct page *kpage, pte_t orig_pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81295780)
Location: mm/ksm.c:1119
Inline: False
Direct callers:
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff81295780-ffffffff81295b4c: replace_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int replace_page(struct vm_area_struct *vma, struct page *page, struct page *kpage, pte_t orig_pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812a55a0)
Location: mm/ksm.c:1119
Inline: False
Direct callers:
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff812a55a0-ffffffff812a5952: replace_page (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
