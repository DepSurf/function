# Function: <code>lru_add_page_tail</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void lru_add_page_tail(struct page *page, struct page *page_tail, struct lruvec *lruvec, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8119e390)
Location: mm/swap.c:994
Inline: False
Direct callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff8119e390-ffffffff8119e553: lru_add_page_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void lru_add_page_tail(struct page *page, struct page *page_tail, struct lruvec *lruvec, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811b3d50)
Location: mm/swap.c:820
Inline: False
Direct callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff811b3d50-ffffffff811b3ffd: lru_add_page_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void lru_add_page_tail(struct page *page, struct page *page_tail, struct lruvec *lruvec, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811c43e0)
Location: mm/swap.c:820
Inline: False
Direct callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff811c43e0-ffffffff811c468b: lru_add_page_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void lru_add_page_tail(struct page *page, struct page *page_tail, struct lruvec *lruvec, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811cc820)
Location: mm/swap.c:833
Inline: False
Direct callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff811cc820-ffffffff811ccac5: lru_add_page_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void lru_add_page_tail(struct page *page, struct page *page_tail, struct lruvec *lruvec, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811e1840)
Location: mm/swap.c:847
Inline: False
Direct callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff811e1840-ffffffff811e1ae5: lru_add_page_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void lru_add_page_tail(struct page *page, struct page *page_tail, struct lruvec *lruvec, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81202f30)
Location: mm/swap.c:819
Inline: False
Direct callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff81202f30-ffffffff812031c4: lru_add_page_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void lru_add_page_tail(struct page *page, struct page *page_tail, struct lruvec *lruvec, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff812158d0)
Location: mm/swap.c:821
Inline: False
Direct callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff812158d0-ffffffff81215b64: lru_add_page_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void lru_add_page_tail(struct page *page, struct page *page_tail, struct lruvec *lruvec, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff812252c0)
Location: mm/swap.c:827
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_page
```
**Symbols:**

```
ffffffff812252c0-ffffffff8122555b: lru_add_page_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void lru_add_page_tail(struct page *page, struct page *page_tail, struct lruvec *lruvec, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81233150)
Location: mm/swap.c:869
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_page
```
**Symbols:**

```
ffffffff81233150-ffffffff812333c8: lru_add_page_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void lru_add_page_tail(struct page *page, struct page *page_tail, struct lruvec *lruvec, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81260790)
Location: mm/swap.c:938
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_page_tail
```
**Symbols:**

```
ffffffff81260790-ffffffff812609a0: lru_add_page_tail (STB_GLOBAL)
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
In mm/huge_memory.c (ffffffff812f3d53)
Location: mm/huge_memory.c:2371
Inline: True
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
In mm/huge_memory.c (ffffffff812fa1b3)
Location: mm/huge_memory.c:2382
Inline: True
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
In mm/huge_memory.c (ffffffff81343ed3)
Location: mm/huge_memory.c:2319
Inline: True
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
In mm/huge_memory.c (ffffffff813b9c1e)
Location: mm/huge_memory.c:2339
Inline: True
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
In mm/huge_memory.c (ffffffff8143c6c6)
Location: mm/huge_memory.c:2409
Inline: True
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
In mm/huge_memory.c (ffffffff81471d0b)
Location: mm/huge_memory.c:2402
Inline: True
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
In mm/huge_memory.c (ffffffff814a2479)
Location: mm/huge_memory.c:2735
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void lru_add_page_tail(struct page *page, struct page *page_tail, struct lruvec *lruvec, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffff8000102c32f0)
Location: mm/swap.c:869
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_page
```
**Symbols:**

```
ffff8000102c32f0-ffff8000102c3584: lru_add_page_tail (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void lru_add_page_tail(struct page *page, struct page *page_tail, struct lruvec *lruvec, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (c00000000037d6a0)
Location: mm/swap.c:869
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_page
```
**Symbols:**

```
c00000000037d6a0-c00000000037d9f0: lru_add_page_tail (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void lru_add_page_tail(struct page *page, struct page *page_tail, struct lruvec *lruvec, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8122b7a0)
Location: mm/swap.c:869
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_page
```
**Symbols:**

```
ffffffff8122b7a0-ffffffff8122ba18: lru_add_page_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void lru_add_page_tail(struct page *page, struct page *page_tail, struct lruvec *lruvec, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8121e890)
Location: mm/swap.c:869
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_page
```
**Symbols:**

```
ffffffff8121e890-ffffffff8121eb08: lru_add_page_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void lru_add_page_tail(struct page *page, struct page *page_tail, struct lruvec *lruvec, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81229540)
Location: mm/swap.c:869
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_page
```
**Symbols:**

```
ffffffff81229540-ffffffff812297b8: lru_add_page_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void lru_add_page_tail(struct page *page, struct page *page_tail, struct lruvec *lruvec, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81238950)
Location: mm/swap.c:869
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_page
```
**Symbols:**

```
ffffffff81238950-ffffffff81238bc8: lru_add_page_tail (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
