# Function: <code>can_split_huge_page</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
bool can_split_huge_page(struct page *page, int *pextra_pins);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81235970)
Location: mm/huge_memory.c:2415
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff81235970-ffffffff81235a0b: can_split_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool can_split_huge_page(struct page *page, int *pextra_pins);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812546c0)
Location: mm/huge_memory.c:2567
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff812546c0-ffffffff8125475b: can_split_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool can_split_huge_page(struct page *page, int *pextra_pins);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81278510)
Location: mm/huge_memory.c:2559
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff81278510-ffffffff812785be: can_split_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool can_split_huge_page(struct page *page, int *pextra_pins);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8128cb70)
Location: mm/huge_memory.c:2578
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff8128cb70-ffffffff8128cc1e: can_split_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool can_split_huge_page(struct page *page, int *pextra_pins);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a7870)
Location: mm/huge_memory.c:2639
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff812a7870-ffffffff812a7925: can_split_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool can_split_huge_page(struct page *page, int *pextra_pins);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812b8d10)
Location: mm/huge_memory.c:2662
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff812b8d10-ffffffff812b8dc5: can_split_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool can_split_huge_page(struct page *page, int *pextra_pins);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812ed8c0)
Location: mm/huge_memory.c:2572
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff812ed8c0-ffffffff812ed972: can_split_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool can_split_huge_page(struct page *page, int *pextra_pins);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812f8f60)
Location: mm/huge_memory.c:2629
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff812f8f60-ffffffff812f9042: can_split_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool can_split_huge_page(struct page *page, int *pextra_pins);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812ff5a0)
Location: mm/huge_memory.c:2640
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff812ff5a0-ffffffff812ff650: can_split_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool can_split_huge_page(struct page *page, int *pextra_pins);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff813491b0)
Location: mm/huge_memory.c:2579
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff813491b0-ffffffff81349260: can_split_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: ✅</summary>

```c
bool can_split_huge_page(struct page *page, int *pextra_pins);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffff800010359400)
Location: mm/huge_memory.c:2662
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffff800010359400-ffff8000103594bc: can_split_huge_page (STB_GLOBAL)
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
In mm/vmscan.c (0)
Location: include/linux/huge_mm.h:318
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool can_split_huge_page(struct page *page, int *pextra_pins);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (c0000000004428c0)
Location: mm/huge_memory.c:2662
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
c0000000004428c0-c0000000004429f0: can_split_huge_page (STB_GLOBAL)
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
In mm/vmscan.c (0)
Location: include/linux/huge_mm.h:318
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
bool can_split_huge_page(struct page *page, int *pextra_pins);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812b12f0)
Location: mm/huge_memory.c:2662
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff812b12f0-ffffffff812b13a5: can_split_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool can_split_huge_page(struct page *page, int *pextra_pins);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a26c0)
Location: mm/huge_memory.c:2662
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff812a26c0-ffffffff812a2775: can_split_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool can_split_huge_page(struct page *page, int *pextra_pins);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812af100)
Location: mm/huge_memory.c:2662
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff812af100-ffffffff812af1b5: can_split_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool can_split_huge_page(struct page *page, int *pextra_pins);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812bf450)
Location: mm/huge_memory.c:2662
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff812bf450-ffffffff812bf505: can_split_huge_page (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
