# Function: <code>stable_tree_search</code>

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
In mm/ksm.c (ffffffff811e5e5a)
Location: mm/ksm.c:1148
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
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
In mm/ksm.c (ffffffff81204bca)
Location: mm/ksm.c:1120
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
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
In mm/ksm.c (ffffffff81216cb4)
Location: mm/ksm.c:1149
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
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
In mm/ksm.c (ffffffff81222698)
Location: mm/ksm.c:1514
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
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
In mm/ksm.c (ffffffff8123da15)
Location: mm/ksm.c:1525
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
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
In mm/ksm.c (ffffffff81260f78)
Location: mm/ksm.c:1555
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
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
In mm/ksm.c (ffffffff81275757)
Location: mm/ksm.c:1553
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct page *stable_tree_search(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81290ac0)
Location: mm/ksm.c:1569
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff81290ac0-ffffffff8129108b: stable_tree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct page *stable_tree_search(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812a0840)
Location: mm/ksm.c:1551
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff812a0840-ffffffff812a0e0b: stable_tree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *stable_tree_search(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812d5210)
Location: mm/ksm.c:1551
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff812d5210-ffffffff812d57c7: stable_tree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *stable_tree_search(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812e0c90)
Location: mm/ksm.c:1552
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff812e0c90-ffffffff812e1241: stable_tree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *stable_tree_search(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812e8390)
Location: mm/ksm.c:1550
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff812e8390-ffffffff812e8941: stable_tree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct page *stable_tree_search(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff813302c0)
Location: mm/ksm.c:1546
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff813302c0-ffffffff81330871: stable_tree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct page *stable_tree_search(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff813a0d20)
Location: mm/ksm.c:1556
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff813a0d20-ffffffff813a149d: stable_tree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct page *stable_tree_search(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff814211a0)
Location: mm/ksm.c:1572
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff814211a0-ffffffff81421956: stable_tree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct page *stable_tree_search(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81455f50)
Location: mm/ksm.c:1618
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff81455f50-ffffffff8145673d: stable_tree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct page *stable_tree_search(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff814909e0)
Location: mm/ksm.c:1817
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff814909e0-ffffffff814911b8: stable_tree_search (STB_LOCAL)
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
struct page *stable_tree_search(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffff800010340158)
Location: mm/ksm.c:1551
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffff800010340158-ffff800010340740: stable_tree_search (STB_LOCAL)
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
In mm/ksm.c (c054676c)
Location: mm/ksm.c:1551
Inline: True
Inline callers:
  - mm/ksm.c:ksm_do_scan
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct page *stable_tree_search(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (c00000000041d480)
Location: mm/ksm.c:1551
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
c00000000041d480-c00000000041dcf0: stable_tree_search (STB_LOCAL)
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
In mm/ksm.c (ffffffe000235064)
Location: mm/ksm.c:1551
Inline: True
Inline callers:
  - mm/ksm.c:ksm_do_scan
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
struct page *stable_tree_search(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81298e20)
Location: mm/ksm.c:1551
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff81298e20-ffffffff812993eb: stable_tree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page *stable_tree_search(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8128a9e0)
Location: mm/ksm.c:1551
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff8128a9e0-ffffffff8128afab: stable_tree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page *stable_tree_search(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81296c30)
Location: mm/ksm.c:1551
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff81296c30-ffffffff812971fb: stable_tree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page *stable_tree_search(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812a6a00)
Location: mm/ksm.c:1551
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff812a6a00-ffffffff812a6fce: stable_tree_search (STB_LOCAL)
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
