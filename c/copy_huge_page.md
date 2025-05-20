# Function: <code>copy_huge_page</code>

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
In mm/migrate.c (ffffffff811f1ae5)
Location: mm/migrate.c:495
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
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
In mm/migrate.c (ffffffff812104b4)
Location: mm/migrate.c:590
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
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
In mm/migrate.c (ffffffff812225e5)
Location: mm/migrate.c:592
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
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
In mm/migrate.c (ffffffff8122e104)
Location: mm/migrate.c:578
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
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
In mm/migrate.c (ffffffff8124a515)
Location: mm/migrate.c:629
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
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
In mm/migrate.c (ffffffff8126d864)
Location: mm/migrate.c:641
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
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
In mm/migrate.c (ffffffff81281e66)
Location: mm/migrate.c:568
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
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
In mm/migrate.c (ffffffff8129df87)
Location: mm/migrate.c:564
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
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
In mm/migrate.c (ffffffff812ad837)
Location: mm/migrate.c:565
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void copy_huge_page(struct page *dst, struct page *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812e26a0)
Location: mm/migrate.c:577
Inline: False
Direct callers:
  - mm/migrate.c:migrate_page_copy
```
**Symbols:**

```
ffffffff812e26a0-ffffffff812e27cb: copy_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void copy_huge_page(struct page *dst, struct page *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812edad0)
Location: mm/migrate.c:574
Inline: False
Direct callers:
  - mm/migrate.c:migrate_page_copy
```
**Symbols:**

```
ffffffff812edad0-ffffffff812edbf9: copy_huge_page (STB_LOCAL)
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
In mm/migrate.c (ffffffff812f4277)
Location: mm/migrate.c:554
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void copy_huge_page(struct page *dst, struct page *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812c1060)
Location: mm/util.c:755
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/migrate.c:migrate_page_copy
```
**Symbols:**

```
ffffffff812c1060-ffffffff812c111a: copy_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
In mm/migrate.c (ffff80001034f808)
Location: mm/migrate.c:565
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
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
In mm/migrate.c (0)
Location: mm/migrate.c:565
Inline: False
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
In mm/migrate.c (c00000000043216c)
Location: mm/migrate.c:565
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
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
In mm/migrate.c (ffffffe00023e690)
Location: mm/migrate.c:565
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
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
In mm/migrate.c (ffffffff812a5e17)
Location: mm/migrate.c:565
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
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
In mm/migrate.c (ffffffff812978c7)
Location: mm/migrate.c:565
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
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
In mm/migrate.c (ffffffff812a3c27)
Location: mm/migrate.c:565
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
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
In mm/migrate.c (ffffffff812b4437)
Location: mm/migrate.c:565
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
