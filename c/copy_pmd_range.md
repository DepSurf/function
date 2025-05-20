# Function: <code>copy_pmd_range</code>

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
In mm/memory.c (ffffffff811c0dda)
Location: mm/memory.c:951
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
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
In mm/memory.c (ffffffff811dc7c6)
Location: mm/memory.c:987
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
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
In mm/memory.c (ffffffff811ec2d6)
Location: mm/memory.c:989
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
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
In mm/memory.c (ffffffff811f71ea)
Location: mm/memory.c:1055
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
In mm/memory.c (ffffffff8120f94b)
Location: mm/memory.c:1122
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
In mm/memory.c (ffffffff812306ea)
Location: mm/memory.c:1136
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
In mm/memory.c (ffffffff81243a5d)
Location: mm/memory.c:879
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
In mm/memory.c (ffffffff812558bb)
Location: mm/memory.c:847
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
In mm/memory.c (ffffffff81263e2b)
Location: mm/memory.c:847
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
In mm/memory.c (ffffffff812941ec)
Location: mm/memory.c:875
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
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
In mm/memory.c (ffffffff8129e915)
Location: mm/memory.c:1029
Inline: True
Inline callers:
  - mm/memory.c:copy_p4d_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int copy_pmd_range(struct vm_area_struct *dst_vma, struct vm_area_struct *src_vma, pud_t *dst_pud, pud_t *src_pud, long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a4940)
Location: mm/memory.c:1036
Inline: False
Direct callers:
  - mm/memory.c:copy_p4d_range
```
**Symbols:**

```
ffffffff812a4940-ffffffff812a4bce: copy_pmd_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int copy_pmd_range(struct vm_area_struct *dst_vma, struct vm_area_struct *src_vma, pud_t *dst_pud, pud_t *src_pud, long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812e3b40)
Location: mm/memory.c:1127
Inline: False
Direct callers:
  - mm/memory.c:copy_p4d_range
```
**Symbols:**

```
ffffffff812e3b40-ffffffff812e3dcd: copy_pmd_range (STB_LOCAL)
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
In mm/memory.c (ffffffff81346ed0)
Location: mm/memory.c:1134
Inline: True
Inline callers:
  - mm/memory.c:copy_p4d_range
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813bf2c4)
Location: mm/memory.c:1091
Inline: True
Inline callers:
  - mm/memory.c:copy_p4d_range
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813f3f44)
Location: mm/memory.c:1138
Inline: True
Inline callers:
  - mm/memory.c:copy_p4d_range
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8141ebd4)
Location: mm/memory.c:1158
Inline: True
Inline callers:
  - mm/memory.c:copy_p4d_range
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
In mm/memory.c (ffff8000102fa650)
Location: mm/memory.c:847
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
In mm/memory.c (c0518b98)
Location: mm/memory.c:847
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
In mm/memory.c (c0000000003c4950)
Location: mm/memory.c:847
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
Location: mm/memory.c:847
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
In mm/memory.c (ffffffff8125c47b)
Location: mm/memory.c:847
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
In mm/memory.c (ffffffff8124ea08)
Location: mm/memory.c:847
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
In mm/memory.c (ffffffff8125a21b)
Location: mm/memory.c:847
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
In mm/memory.c (ffffffff81269c1b)
Location: mm/memory.c:847
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
