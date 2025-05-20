# Function: <code>__get_huge_page_for_hwpoison</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __get_huge_page_for_hwpoison(long unsigned int pfn, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff813dd030)
Location: mm/memory-failure.c:1511
Inline: False
Direct callers:
  - mm/hugetlb.c:get_huge_page_for_hwpoison
```
**Symbols:**

```
ffffffff813dd030-ffffffff813dd156: __get_huge_page_for_hwpoison (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __get_huge_page_for_hwpoison(long unsigned int pfn, int flags, bool *migratable_cleared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81463c50)
Location: mm/memory-failure.c:1806
Inline: False
Direct callers:
  - mm/hugetlb.c:get_huge_page_for_hwpoison
```
**Symbols:**

```
ffffffff81463c50-ffffffff81463f1a: __get_huge_page_for_hwpoison (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __get_huge_page_for_hwpoison(long unsigned int pfn, int flags, bool *migratable_cleared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff814997c0)
Location: mm/memory-failure.c:1934
Inline: False
Direct callers:
  - mm/hugetlb.c:get_huge_page_for_hwpoison
```
**Symbols:**

```
ffffffff814997c0-ffffffff814999da: __get_huge_page_for_hwpoison (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __get_huge_page_for_hwpoison(long unsigned int pfn, int flags, bool *migratable_cleared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff814c8f30)
Location: mm/memory-failure.c:1987
Inline: False
Direct callers:
  - mm/hugetlb.c:get_huge_page_for_hwpoison
```
**Symbols:**

```
ffffffff814c8f30-ffffffff814c9178: __get_huge_page_for_hwpoison (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool *migratable_cleared</code>
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
