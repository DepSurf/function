# Function: <code>__page_handle_poison</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool __page_handle_poison(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff8135e350)
Location: mm/memory-failure.c:69
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:page_handle_poison
```
**Symbols:**

```
ffffffff8135e350-ffffffff8135e40a: __page_handle_poison (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool __page_handle_poison(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff813d8a50)
Location: mm/memory-failure.c:74
Inline: False
Direct callers:
  - mm/memory-failure.c:try_memory_failure_hugetlb
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:page_handle_poison
```
**Symbols:**

```
ffffffff813d8a50-ffffffff813d8b17: __page_handle_poison (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __page_handle_poison(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff8145e730)
Location: mm/memory-failure.c:96
Inline: False
Direct callers:
  - mm/memory-failure.c:try_memory_failure_hugetlb
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:page_handle_poison
```
**Symbols:**

```
ffffffff8145e730-ffffffff8145e7f7: __page_handle_poison (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __page_handle_poison(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81494580)
Location: mm/memory-failure.c:154
Inline: False
Direct callers:
  - mm/memory-failure.c:try_memory_failure_hugetlb
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:page_handle_poison
```
**Symbols:**

```
ffffffff81494580-ffffffff81494647: __page_handle_poison (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __page_handle_poison(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff814c3de0)
Location: mm/memory-failure.c:153
Inline: False
Direct callers:
  - mm/memory-failure.c:try_memory_failure_hugetlb
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:page_handle_poison
```
**Symbols:**

```
ffffffff814c3de0-ffffffff814c3ea7: __page_handle_poison (STB_LOCAL)
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
