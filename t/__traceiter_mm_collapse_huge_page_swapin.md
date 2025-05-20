# Function: <code>__traceiter_mm_collapse_huge_page_swapin</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __traceiter_mm_collapse_huge_page_swapin(void *__data, struct mm_struct *mm, int swapped_in, int referenced, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812fa480)
Location: include/trace/events/huge_memory.h:143
Inline: False
```
**Symbols:**

```
ffffffff812fa480-ffffffff812fa4db: __traceiter_mm_collapse_huge_page_swapin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_mm_collapse_huge_page_swapin(void *__data, struct mm_struct *mm, int swapped_in, int referenced, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff81301240)
Location: include/trace/events/huge_memory.h:143
Inline: False
```
**Symbols:**

```
ffffffff81301240-ffffffff81301299: __traceiter_mm_collapse_huge_page_swapin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_mm_collapse_huge_page_swapin(void *__data, struct mm_struct *mm, int swapped_in, int referenced, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8134aeb0)
Location: include/trace/events/huge_memory.h:143
Inline: False
```
**Symbols:**

```
ffffffff8134aeb0-ffffffff8134af09: __traceiter_mm_collapse_huge_page_swapin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_mm_collapse_huge_page_swapin(void *__data, struct mm_struct *mm, int swapped_in, int referenced, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff813c21a0)
Location: include/trace/events/huge_memory.h:142
Inline: False
```
**Symbols:**

```
ffffffff813c21a0-ffffffff813c2208: __traceiter_mm_collapse_huge_page_swapin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_mm_collapse_huge_page_swapin(void *__data, struct mm_struct *mm, int swapped_in, int referenced, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff814444c0)
Location: include/trace/events/huge_memory.h:145
Inline: False
```
**Symbols:**

```
ffffffff814444c0-ffffffff81444528: __traceiter_mm_collapse_huge_page_swapin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_mm_collapse_huge_page_swapin(void *__data, struct mm_struct *mm, int swapped_in, int referenced, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff81479a90)
Location: include/trace/events/huge_memory.h:148
Inline: False
```
**Symbols:**

```
ffffffff81479a90-ffffffff81479af8: __traceiter_mm_collapse_huge_page_swapin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_mm_collapse_huge_page_swapin(void *__data, struct mm_struct *mm, int swapped_in, int referenced, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff814a9030)
Location: include/trace/events/huge_memory.h:148
Inline: False
```
**Symbols:**

```
ffffffff814a9030-ffffffff814a9098: __traceiter_mm_collapse_huge_page_swapin (STB_GLOBAL)
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
