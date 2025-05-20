# Function: <code>hugetlb_unshare_all_pmds</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void hugetlb_unshare_all_pmds(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812de800)
Location: mm/hugetlb.c:6001
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_register
```
**Symbols:**

```
ffffffff812de800-ffffffff812dea4d: hugetlb_unshare_all_pmds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void hugetlb_unshare_all_pmds(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:6338
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_register
```
**Symbols:**

```
ffffffff81cc04b4-ffffffff81cc04ed: hugetlb_unshare_all_pmds.cold (STB_LOCAL)
ffffffff81325bd0-ffffffff81325e32: hugetlb_unshare_all_pmds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void hugetlb_unshare_all_pmds(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:7079
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_register
```
**Symbols:**

```
ffffffff81e728d1-ffffffff81e7290a: hugetlb_unshare_all_pmds.cold (STB_LOCAL)
ffffffff81394920-ffffffff81394b9d: hugetlb_unshare_all_pmds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void hugetlb_unshare_all_pmds(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81413380)
Location: mm/hugetlb.c:7408
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_register
```
**Symbols:**

```
ffffffff81413380-ffffffff814133b8: hugetlb_unshare_all_pmds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void hugetlb_unshare_all_pmds(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff814468e0)
Location: mm/hugetlb.c:7507
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_register
```
**Symbols:**

```
ffffffff814468e0-ffffffff81446918: hugetlb_unshare_all_pmds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void hugetlb_unshare_all_pmds(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81480380)
Location: mm/hugetlb.c:7644
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_register
```
**Symbols:**

```
ffffffff81480380-ffffffff814803b8: hugetlb_unshare_all_pmds (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
