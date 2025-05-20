# Function: <code>__traceiter_mm_collapse_huge_page</code>

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
int __traceiter_mm_collapse_huge_page(void *__data, struct mm_struct *mm, int isolated, int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812fa3b0)
Location: include/trace/events/huge_memory.h:88
Inline: False
```
**Symbols:**

```
ffffffff812fa3b0-ffffffff812fa401: __traceiter_mm_collapse_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_mm_collapse_huge_page(void *__data, struct mm_struct *mm, int isolated, int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff81301180)
Location: include/trace/events/huge_memory.h:88
Inline: False
```
**Symbols:**

```
ffffffff81301180-ffffffff813011cf: __traceiter_mm_collapse_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_mm_collapse_huge_page(void *__data, struct mm_struct *mm, int isolated, int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8134adf0)
Location: include/trace/events/huge_memory.h:88
Inline: False
```
**Symbols:**

```
ffffffff8134adf0-ffffffff8134ae3f: __traceiter_mm_collapse_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_mm_collapse_huge_page(void *__data, struct mm_struct *mm, int isolated, int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff813c20b0)
Location: include/trace/events/huge_memory.h:87
Inline: False
```
**Symbols:**

```
ffffffff813c20b0-ffffffff813c210b: __traceiter_mm_collapse_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_mm_collapse_huge_page(void *__data, struct mm_struct *mm, int isolated, int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff814443b0)
Location: include/trace/events/huge_memory.h:90
Inline: False
```
**Symbols:**

```
ffffffff814443b0-ffffffff8144440b: __traceiter_mm_collapse_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_mm_collapse_huge_page(void *__data, struct mm_struct *mm, int isolated, int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff81479940)
Location: include/trace/events/huge_memory.h:93
Inline: False
```
**Symbols:**

```
ffffffff81479940-ffffffff8147999b: __traceiter_mm_collapse_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_mm_collapse_huge_page(void *__data, struct mm_struct *mm, int isolated, int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff814a8ee0)
Location: include/trace/events/huge_memory.h:93
Inline: False
```
**Symbols:**

```
ffffffff814a8ee0-ffffffff814a8f3b: __traceiter_mm_collapse_huge_page (STB_GLOBAL)
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
