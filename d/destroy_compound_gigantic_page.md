# Function: <code>destroy_compound_gigantic_page</code>

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
In mm/hugetlb.c (ffffffff811da9c6)
Location: mm/hugetlb.c:1006
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
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
In mm/hugetlb.c (ffffffff811f8b66)
Location: mm/hugetlb.c:1028
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
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
In mm/hugetlb.c (ffffffff81209576)
Location: mm/hugetlb.c:1028
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
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
In mm/hugetlb.c (ffffffff81214e24)
Location: mm/hugetlb.c:1046
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
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
In mm/hugetlb.c (ffffffff8122fb4a)
Location: mm/hugetlb.c:1047
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
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
In mm/hugetlb.c (ffffffff81251f8e)
Location: mm/hugetlb.c:1039
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
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
In mm/hugetlb.c (ffffffff8126638c)
Location: mm/hugetlb.c:1039
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
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
In mm/hugetlb.c (ffffffff8128150c)
Location: mm/hugetlb.c:1049
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
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
In mm/hugetlb.c (ffffffff8129100c)
Location: mm/hugetlb.c:1050
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void destroy_compound_gigantic_page(struct page *page, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812c3f10)
Location: mm/hugetlb.c:1215
Inline: False
Direct callers:
  - mm/hugetlb.c:update_and_free_page
```
**Symbols:**

```
ffffffff812c3f10-ffffffff812c4051: destroy_compound_gigantic_page (STB_LOCAL)
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
In mm/hugetlb.c (ffffffff812d0884)
Location: mm/hugetlb.c:1240
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
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
In mm/hugetlb.c (ffffffff812d61a7)
Location: mm/hugetlb.c:1250
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
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
In mm/hugetlb.c (ffffffff8131d7b4)
Location: mm/hugetlb.c:1264
Inline: True
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
In mm/hugetlb.c (ffffffff81388e28)
Location: mm/hugetlb.c:1343
Inline: True
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In mm/hugetlb.c (ffff80001032e480)
Location: mm/hugetlb.c:1050
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (c000000000406fe4)
Location: mm/hugetlb.c:1050
Inline: True
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
In mm/hugetlb.c (ffffffe00022c2ac)
Location: mm/hugetlb.c:1050
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
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
In mm/hugetlb.c (ffffffff812895ec)
Location: mm/hugetlb.c:1050
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
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
In mm/hugetlb.c (ffffffff8127b48c)
Location: mm/hugetlb.c:1050
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
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
In mm/hugetlb.c (ffffffff812873fc)
Location: mm/hugetlb.c:1050
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
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
In mm/hugetlb.c (ffffffff81297b3c)
Location: mm/hugetlb.c:1050
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
