# Function: <code>collapse_shmem</code>

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
void collapse_shmem(struct mm_struct *mm, struct address_space *mapping, long unsigned int start, struct page **hpage, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8121ab40)
Location: mm/khugepaged.c:1294
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffffffff8121ab40-ffffffff8121b78f: collapse_shmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void collapse_shmem(struct mm_struct *mm, struct address_space *mapping, long unsigned int start, struct page **hpage, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8122c330)
Location: mm/khugepaged.c:1296
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffffffff8122c330-ffffffff8122cf4c: collapse_shmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void collapse_shmem(struct mm_struct *mm, struct address_space *mapping, long unsigned int start, struct page **hpage, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff81238ba0)
Location: mm/khugepaged.c:1297
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffffffff81238ba0-ffffffff812396a5: collapse_shmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void collapse_shmem(struct mm_struct *mm, struct address_space *mapping, long unsigned int start, struct page **hpage, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812572a0)
Location: mm/khugepaged.c:1303
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffffffff812572a0-ffffffff81257e5e: collapse_shmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void collapse_shmem(struct mm_struct *mm, struct address_space *mapping, long unsigned int start, struct page **hpage, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8127b210)
Location: mm/khugepaged.c:1303
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
**Symbols:**

```
ffffffff8127b210-ffffffff8127bdb9: collapse_shmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void collapse_shmem(struct mm_struct *mm, struct address_space *mapping, long unsigned int start, struct page **hpage, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8128f820)
Location: mm/khugepaged.c:1302
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffffffff8128f820-ffffffff8129041c: collapse_shmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void collapse_shmem(struct mm_struct *mm, struct address_space *mapping, long unsigned int start, struct page **hpage, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812aa8a0)
Location: mm/khugepaged.c:1307
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffffffff812aa8a0-ffffffff812ab558: collapse_shmem (STB_LOCAL)
```
</details>
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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
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
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
</ul>
