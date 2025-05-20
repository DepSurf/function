# Function: <code>take_page_off_buddy</code>

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
bool take_page_off_buddy(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812c0170)
Location: mm/page_alloc.c:8931
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:me_huge_page
```
**Symbols:**

```
ffffffff812c0170-ffffffff812c0428: take_page_off_buddy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool take_page_off_buddy(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812c58e0)
Location: mm/page_alloc.c:9156
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:me_huge_page
```
**Symbols:**

```
ffffffff812c58e0-ffffffff812c5bca: take_page_off_buddy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool take_page_off_buddy(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:9421
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:__page_handle_poison
```
**Symbols:**

```
ffffffff81cbe53d-ffffffff81cbe574: take_page_off_buddy.cold (STB_LOCAL)
ffffffff81309ff0-ffffffff8130a41d: take_page_off_buddy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool take_page_off_buddy(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:9474
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:__page_handle_poison
```
**Symbols:**

```
ffffffff81e7051e-ffffffff81e70557: take_page_off_buddy.cold (STB_LOCAL)
ffffffff81372890-ffffffff81372d28: take_page_off_buddy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool take_page_off_buddy(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:9639
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:__page_handle_poison
```
**Symbols:**

```
ffffffff820656ae-ffffffff820656e7: take_page_off_buddy.cold (STB_LOCAL)
ffffffff813f0000-ffffffff813f0498: take_page_off_buddy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool take_page_off_buddy(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:6546
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:__page_handle_poison
```
**Symbols:**

```
ffffffff820e4ea7-ffffffff820e4ed8: take_page_off_buddy.cold (STB_LOCAL)
ffffffff81423b80-ffffffff81424022: take_page_off_buddy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool take_page_off_buddy(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:6685
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:__page_handle_poison
```
**Symbols:**

```
ffffffff821c1b86-ffffffff821c1baf: take_page_off_buddy.cold (STB_LOCAL)
ffffffff81450ac0-ffffffff81450ec2: take_page_off_buddy (STB_GLOBAL)
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
