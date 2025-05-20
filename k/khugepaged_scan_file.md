# Function: <code>khugepaged_scan_file</code>

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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812be2eb)
Location: mm/khugepaged.c:1814
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void khugepaged_scan_file(struct mm_struct *mm, struct file *file, long unsigned int start, struct page **hpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812f2190)
Location: mm/khugepaged.c:1940
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
**Symbols:**

```
ffffffff812f2190-ffffffff812f24c5: khugepaged_scan_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void khugepaged_scan_file(struct mm_struct *mm, struct file *file, long unsigned int start, struct page **hpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812fe640)
Location: mm/khugepaged.c:1977
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
**Symbols:**

```
ffffffff812fe640-ffffffff812fe991: khugepaged_scan_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void khugepaged_scan_file(struct mm_struct *mm, struct file *file, long unsigned int start, struct page **hpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff813052c0)
Location: mm/khugepaged.c:1968
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
**Symbols:**

```
ffffffff813052c0-ffffffff8130560c: khugepaged_scan_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void khugepaged_scan_file(struct mm_struct *mm, struct file *file, long unsigned int start, struct page **hpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8134f110)
Location: mm/khugepaged.c:1990
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
**Symbols:**

```
ffffffff8134f110-ffffffff8134f46f: khugepaged_scan_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void khugepaged_scan_file(struct mm_struct *mm, struct file *file, long unsigned int start, struct page **hpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff813c5d10)
Location: mm/khugepaged.c:1997
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
**Symbols:**

```
ffffffff813c5d10-ffffffff813c60d5: khugepaged_scan_file (STB_LOCAL)
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
In mm/khugepaged.c (ffff80001035fc44)
Location: mm/khugepaged.c:1814
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
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
In mm/khugepaged.c (c00000000044a9c8)
Location: mm/khugepaged.c:1814
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812b68cb)
Location: mm/khugepaged.c:1814
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
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
In mm/khugepaged.c (ffffffff812a7a9b)
Location: mm/khugepaged.c:1814
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
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
In mm/khugepaged.c (ffffffff812b46db)
Location: mm/khugepaged.c:1814
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
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
In mm/khugepaged.c (ffffffff812c508f)
Location: mm/khugepaged.c:1814
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
