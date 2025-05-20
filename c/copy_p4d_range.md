# Function: <code>copy_p4d_range</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f71ea)
Location: mm/memory.c:1122
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
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
In mm/memory.c (ffffffff8120f7a7)
Location: mm/memory.c:1190
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
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
In mm/memory.c (ffffffff8123056d)
Location: mm/memory.c:1204
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
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
In mm/memory.c (ffffffff812438da)
Location: mm/memory.c:947
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
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
In mm/memory.c (ffffffff81255726)
Location: mm/memory.c:915
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
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
In mm/memory.c (ffffffff81263c96)
Location: mm/memory.c:915
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
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
In mm/memory.c (ffffffff81293ee7)
Location: mm/memory.c:943
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int copy_p4d_range(struct vm_area_struct *dst_vma, struct vm_area_struct *src_vma, pgd_t *dst_pgd, pgd_t *src_pgd, long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129e670)
Location: mm/memory.c:1103
Inline: False
Direct callers:
  - mm/memory.c:copy_page_range
```
**Symbols:**

```
ffffffff8129e670-ffffffff8129ec14: copy_p4d_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int copy_p4d_range(struct vm_area_struct *dst_vma, struct vm_area_struct *src_vma, pgd_t *dst_pgd, pgd_t *src_pgd, long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a4bd0)
Location: mm/memory.c:1110
Inline: False
Direct callers:
  - mm/memory.c:copy_page_range
```
**Symbols:**

```
ffffffff812a4bd0-ffffffff812a4efe: copy_p4d_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int copy_p4d_range(struct vm_area_struct *dst_vma, struct vm_area_struct *src_vma, pgd_t *dst_pgd, pgd_t *src_pgd, long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812e3dd0)
Location: mm/memory.c:1201
Inline: False
Direct callers:
  - mm/memory.c:copy_page_range
```
**Symbols:**

```
ffffffff812e3dd0-ffffffff812e40f5: copy_p4d_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int copy_p4d_range(struct vm_area_struct *dst_vma, struct vm_area_struct *src_vma, pgd_t *dst_pgd, pgd_t *src_pgd, long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81346c30)
Location: mm/memory.c:1208
Inline: False
Direct callers:
  - mm/memory.c:copy_page_range
```
**Symbols:**

```
ffffffff81346c30-ffffffff813471f3: copy_p4d_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int copy_p4d_range(struct vm_area_struct *dst_vma, struct vm_area_struct *src_vma, pgd_t *dst_pgd, pgd_t *src_pgd, long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813bf030)
Location: mm/memory.c:1165
Inline: False
Direct callers:
  - mm/memory.c:copy_page_range
```
**Symbols:**

```
ffffffff813bf030-ffffffff813bf5f0: copy_p4d_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int copy_p4d_range(struct vm_area_struct *dst_vma, struct vm_area_struct *src_vma, pgd_t *dst_pgd, pgd_t *src_pgd, long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813f3cb0)
Location: mm/memory.c:1212
Inline: False
Direct callers:
  - mm/memory.c:copy_page_range
```
**Symbols:**

```
ffffffff813f3cb0-ffffffff813f4270: copy_p4d_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int copy_p4d_range(struct vm_area_struct *dst_vma, struct vm_area_struct *src_vma, pgd_t *dst_pgd, pgd_t *src_pgd, long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8141e940)
Location: mm/memory.c:1232
Inline: False
Direct callers:
  - mm/memory.c:copy_page_range
```
**Symbols:**

```
ffffffff8141e940-ffffffff8141ef00: copy_p4d_range (STB_LOCAL)
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
In mm/memory.c (ffff8000102fa5ac)
Location: mm/memory.c:915
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
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
In mm/memory.c (c0518b90)
Location: mm/memory.c:915
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
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
In mm/memory.c (c0000000003c4814)
Location: mm/memory.c:915
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
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
In mm/memory.c (ffffffe000209c8e)
Location: mm/memory.c:915
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
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
In mm/memory.c (ffffffff8125c2e6)
Location: mm/memory.c:915
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
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
In mm/memory.c (ffffffff8124e87f)
Location: mm/memory.c:915
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
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
In mm/memory.c (ffffffff8125a086)
Location: mm/memory.c:915
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
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
In mm/memory.c (ffffffff81269a86)
Location: mm/memory.c:915
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
