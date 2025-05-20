# Function: <code>free_unref_page_list</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_unref_page_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d5c90)
Location: mm/page_alloc.c:2688
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff811d5c90-ffffffff811d5e19: free_unref_page_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_unref_page_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811f70c0)
Location: mm/page_alloc.c:2792
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff811f70c0-ffffffff811f7248: free_unref_page_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_unref_page_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812094e0)
Location: mm/page_alloc.c:2891
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff812094e0-ffffffff81209668: free_unref_page_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void free_unref_page_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812707f0)
Location: mm/page_alloc.c:3067
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff812707f0-ffffffff8127097c: free_unref_page_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void free_unref_page_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8127f630)
Location: mm/page_alloc.c:3058
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff8127f630-ffffffff8127f7bc: free_unref_page_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void free_unref_page_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812b1c60)
Location: mm/page_alloc.c:3150
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff812b1c60-ffffffff812b1e56: free_unref_page_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void free_unref_page_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812bd660)
Location: mm/page_alloc.c:3250
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff812bd660-ffffffff812bd827: free_unref_page_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void free_unref_page_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812c25f0)
Location: mm/page_alloc.c:3299
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff812c25f0-ffffffff812c27d2: free_unref_page_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void free_unref_page_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81305fc0)
Location: mm/page_alloc.c:3423
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff81305fc0-ffffffff813062a9: free_unref_page_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void free_unref_page_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8136e0c0)
Location: mm/page_alloc.c:3461
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/swap.c:put_pages_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff8136e0c0-ffffffff8136e375: free_unref_page_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void free_unref_page_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813ea410)
Location: mm/page_alloc.c:3498
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/swap.c:put_pages_list
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_folio_list
```
**Symbols:**

```
ffffffff813ea410-ffffffff813ea860: free_unref_page_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void free_unref_page_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8141f3d0)
Location: mm/page_alloc.c:2477
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/swap.c:put_pages_list
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_folio_list
```
**Symbols:**

```
ffffffff8141f3d0-ffffffff8141f7a0: free_unref_page_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void free_unref_page_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8144c090)
Location: mm/page_alloc.c:2520
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/swap.c:put_pages_list
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_folio_list
```
**Symbols:**

```
ffffffff8144c090-ffffffff8144c4ae: free_unref_page_list (STB_GLOBAL)
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
void free_unref_page_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff8000103172c8)
Location: mm/page_alloc.c:3058
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffff8000103172c8-ffff8000103174d0: free_unref_page_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void free_unref_page_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c05319b8)
Location: mm/page_alloc.c:3058
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
c05319b8-c0531ba4: free_unref_page_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void free_unref_page_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003e9670)
Location: mm/page_alloc.c:3058
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
c0000000003e9670-c0000000003e98d8: free_unref_page_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void free_unref_page_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe00021d510)
Location: mm/page_alloc.c:3058
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffe00021d510-ffffffe00021d692: free_unref_page_list (STB_GLOBAL)
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
void free_unref_page_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81277c80)
Location: mm/page_alloc.c:3058
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff81277c80-ffffffff81277e0c: free_unref_page_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void free_unref_page_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81269b90)
Location: mm/page_alloc.c:3058
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff81269b90-ffffffff81269cf4: free_unref_page_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void free_unref_page_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81275a20)
Location: mm/page_alloc.c:3058
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff81275a20-ffffffff81275bac: free_unref_page_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void free_unref_page_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812855e0)
Location: mm/page_alloc.c:3058
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff812855e0-ffffffff81285788: free_unref_page_list (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
