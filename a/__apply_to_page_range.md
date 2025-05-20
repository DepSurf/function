# Function: <code>__apply_to_page_range</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __apply_to_page_range(struct mm_struct *mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void *data, bool create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812936c0)
Location: mm/memory.c:2331
Inline: False
Direct callers:
  - mm/memory.c:apply_to_existing_page_range
  - mm/memory.c:apply_to_page_range
```
**Symbols:**

```
ffffffff812936c0-ffffffff8129385d: __apply_to_page_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __apply_to_page_range(struct mm_struct *mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void *data, bool create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129db10)
Location: mm/memory.c:2510
Inline: False
Direct callers:
  - mm/memory.c:apply_to_existing_page_range
  - mm/memory.c:apply_to_page_range
```
**Symbols:**

```
ffffffff8129db10-ffffffff8129e148: __apply_to_page_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __apply_to_page_range(struct mm_struct *mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void *data, bool create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a35a0)
Location: mm/memory.c:2563
Inline: False
Direct callers:
  - mm/memory.c:apply_to_existing_page_range
  - mm/memory.c:apply_to_page_range
```
**Symbols:**

```
ffffffff812a35a0-ffffffff812a3877: __apply_to_page_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __apply_to_page_range(struct mm_struct *mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void *data, bool create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:2658
Inline: False
Direct callers:
  - mm/memory.c:apply_to_existing_page_range
  - mm/memory.c:apply_to_page_range
```
**Symbols:**

```
ffffffff812e4850-ffffffff812e4b7d: __apply_to_page_range (STB_LOCAL)
ffffffff81cbc4fe-ffffffff81cbc577: __apply_to_page_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __apply_to_page_range(struct mm_struct *mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void *data, bool create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:2751
Inline: False
Direct callers:
  - mm/memory.c:apply_to_existing_page_range
  - mm/memory.c:apply_to_page_range
```
**Symbols:**

```
ffffffff81346150-ffffffff81346484: __apply_to_page_range (STB_LOCAL)
ffffffff81e6e052-ffffffff81e6e0de: __apply_to_page_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __apply_to_page_range(struct mm_struct *mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void *data, bool create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:2722
Inline: False
Direct callers:
  - mm/memory.c:apply_to_existing_page_range
  - mm/memory.c:apply_to_page_range
```
**Symbols:**

```
ffffffff813be520-ffffffff813be838: __apply_to_page_range (STB_LOCAL)
ffffffff82064054-ffffffff820640e0: __apply_to_page_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __apply_to_page_range(struct mm_struct *mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void *data, bool create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:2722
Inline: False
Direct callers:
  - mm/memory.c:apply_to_existing_page_range
  - mm/memory.c:apply_to_page_range
```
**Symbols:**

```
ffffffff813f3180-ffffffff813f3488: __apply_to_page_range (STB_LOCAL)
ffffffff820e3740-ffffffff820e37cd: __apply_to_page_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __apply_to_page_range(struct mm_struct *mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void *data, bool create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:2745
Inline: False
Direct callers:
  - mm/memory.c:apply_to_existing_page_range
  - mm/memory.c:apply_to_page_range
```
**Symbols:**

```
ffffffff8141de70-ffffffff8141e178: __apply_to_page_range (STB_LOCAL)
ffffffff821c0189-ffffffff821c0216: __apply_to_page_range.cold (STB_LOCAL)
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
