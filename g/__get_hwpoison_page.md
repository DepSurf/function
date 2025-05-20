# Function: <code>__get_hwpoison_page</code>

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
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __get_hwpoison_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:955
Inline: False
Direct callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
```
**Symbols:**

```
ffffffff8130c5f0-ffffffff8130c688: __get_hwpoison_page (STB_LOCAL)
ffffffff81be9f87-ffffffff81be9fd0: __get_hwpoison_page.cold (STB_LOCAL)
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
In mm/memory-failure.c (ffffffff81314232)
Location: mm/memory-failure.c:977
Inline: True
Inline callers:
  - mm/memory-failure.c:get_any_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff8135f644)
Location: mm/memory-failure.c:1132
Inline: True
Inline callers:
  - mm/memory-failure.c:get_any_page
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
In mm/memory-failure.c (ffffffff813db467)
Location: mm/memory-failure.c:1191
Inline: True
Inline callers:
  - mm/memory-failure.c:get_any_page
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
In mm/memory-failure.c (ffffffff814602e3)
Location: mm/memory-failure.c:1258
Inline: True
Inline callers:
  - mm/memory-failure.c:get_any_page
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
In mm/memory-failure.c (ffffffff81496589)
Location: mm/memory-failure.c:1391
Inline: True
Inline callers:
  - mm/memory-failure.c:get_any_page
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
In mm/memory-failure.c (ffffffff814c5a2e)
Location: mm/memory-failure.c:1390
Inline: True
Inline callers:
  - mm/memory-failure.c:get_any_page
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
</ul>
