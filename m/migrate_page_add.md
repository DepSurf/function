# Function: <code>migrate_page_add</code>

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
In mm/mempolicy.c (ffffffff811e013c)
Location: mm/mempolicy.c:924
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
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
In mm/mempolicy.c (ffffffff811feda9)
Location: mm/mempolicy.c:956
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
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
In mm/mempolicy.c (ffffffff812105e5)
Location: mm/mempolicy.c:958
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
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
In mm/mempolicy.c (ffffffff8121c166)
Location: mm/mempolicy.c:886
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void migrate_page_add(struct page *page, struct list_head *pagelist, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81236960)
Location: mm/mempolicy.c:928
Inline: False
Direct callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
**Symbols:**

```
ffffffff81236960-ffffffff81236a26: migrate_page_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void migrate_page_add(struct page *page, struct list_head *pagelist, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81259930)
Location: mm/mempolicy.c:903
Inline: False
Direct callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
**Symbols:**

```
ffffffff81259930-ffffffff812599f6: migrate_page_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void migrate_page_add(struct page *page, struct list_head *pagelist, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8126d540)
Location: mm/mempolicy.c:943
Inline: False
Direct callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
**Symbols:**

```
ffffffff8126d540-ffffffff8126d608: migrate_page_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int migrate_page_add(struct page *page, struct list_head *pagelist, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81288a60)
Location: mm/mempolicy.c:970
Inline: False
Direct callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
**Symbols:**

```
ffffffff81288a60-ffffffff81288b65: migrate_page_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int migrate_page_add(struct page *page, struct list_head *pagelist, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812985d0)
Location: mm/mempolicy.c:971
Inline: False
Direct callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
**Symbols:**

```
ffffffff812985d0-ffffffff812986d5: migrate_page_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int migrate_page_add(struct page *page, struct list_head *pagelist, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812cc140)
Location: mm/mempolicy.c:1040
Inline: False
Direct callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
**Symbols:**

```
ffffffff812cc140-ffffffff812cc246: migrate_page_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int migrate_page_add(struct page *page, struct list_head *pagelist, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812d79d0)
Location: mm/mempolicy.c:1039
Inline: False
Direct callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
**Symbols:**

```
ffffffff812d79d0-ffffffff812d7ad5: migrate_page_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int migrate_page_add(struct page *page, struct list_head *pagelist, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812deef0)
Location: mm/mempolicy.c:1049
Inline: False
Direct callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
**Symbols:**

```
ffffffff812deef0-ffffffff812deff1: migrate_page_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int migrate_page_add(struct page *page, struct list_head *pagelist, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81326b80)
Location: mm/mempolicy.c:1020
Inline: False
Direct callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
**Symbols:**

```
ffffffff81326b80-ffffffff81326c81: migrate_page_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int migrate_page_add(struct page *page, struct list_head *pagelist, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff813961c0)
Location: mm/mempolicy.c:1016
Inline: False
Direct callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
**Symbols:**

```
ffffffff813961c0-ffffffff81396350: migrate_page_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int migrate_page_add(struct page *page, struct list_head *pagelist, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff814161b0)
Location: mm/mempolicy.c:1030
Inline: False
Direct callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
**Symbols:**

```
ffffffff814161b0-ffffffff81416387: migrate_page_add (STB_LOCAL)
```
</details>
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
<summary>In <code>arm64</code>: ✅</summary>

```c
int migrate_page_add(struct page *page, struct list_head *pagelist, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffff800010337210)
Location: mm/mempolicy.c:971
Inline: False
Direct callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
**Symbols:**

```
ffff800010337210-ffff800010337320: migrate_page_add (STB_LOCAL)
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
int migrate_page_add(struct page *page, struct list_head *pagelist, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (c000000000411bb0)
Location: mm/mempolicy.c:971
Inline: False
Direct callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
**Symbols:**

```
c000000000411bb0-c000000000411d68: migrate_page_add (STB_LOCAL)
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
int migrate_page_add(struct page *page, struct list_head *pagelist, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81290bb0)
Location: mm/mempolicy.c:971
Inline: False
Direct callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
**Symbols:**

```
ffffffff81290bb0-ffffffff81290cb5: migrate_page_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int migrate_page_add(struct page *page, struct list_head *pagelist, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81282830)
Location: mm/mempolicy.c:971
Inline: False
Direct callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
**Symbols:**

```
ffffffff81282830-ffffffff81282935: migrate_page_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int migrate_page_add(struct page *page, struct list_head *pagelist, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8128e9c0)
Location: mm/mempolicy.c:971
Inline: False
Direct callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
**Symbols:**

```
ffffffff8128e9c0-ffffffff8128eac5: migrate_page_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int migrate_page_add(struct page *page, struct list_head *pagelist, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8129e8c0)
Location: mm/mempolicy.c:971
Inline: False
Direct callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
**Symbols:**

```
ffffffff8129e8c0-ffffffff8129e9c5: migrate_page_add (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
