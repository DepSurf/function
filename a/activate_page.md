# Function: <code>activate_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void activate_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8119dd80)
Location: mm/swap.c:536
Inline: True
Direct callers:
  - mm/swap.c:mark_page_accessed
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
```
**Symbols:**

```
ffffffff8119dd80-ffffffff8119ddfc: activate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void activate_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811b3480)
Location: mm/swap.c:293
Inline: False
Direct callers:
  - mm/swap.c:mark_page_accessed
  - mm/memory.c:do_swap_page
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
```
**Symbols:**

```
ffffffff811b3480-ffffffff811b355a: activate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void activate_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811c3b00)
Location: mm/swap.c:294
Inline: False
Direct callers:
  - mm/swap.c:mark_page_accessed
  - mm/memory.c:do_swap_page
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
```
**Symbols:**

```
ffffffff811c3b00-ffffffff811c3bda: activate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void activate_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811cbed0)
Location: mm/swap.c:305
Inline: False
Direct callers:
  - mm/swap.c:mark_page_accessed
  - mm/memory.c:do_swap_page
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
```
**Symbols:**

```
ffffffff811cbed0-ffffffff811cbf8d: activate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void activate_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811e0ec0)
Location: mm/swap.c:305
Inline: False
Direct callers:
  - mm/swap.c:mark_page_accessed
  - mm/memory.c:do_swap_page
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
```
**Symbols:**

```
ffffffff811e0ec0-ffffffff811e0f7c: activate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void activate_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81202750)
Location: mm/swap.c:306
Inline: False
Direct callers:
  - mm/swap.c:mark_page_accessed
  - mm/memory.c:do_swap_page
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_vma
```
**Symbols:**

```
ffffffff81202750-ffffffff8120280b: activate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void activate_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff812150d0)
Location: mm/swap.c:305
Inline: False
Direct callers:
  - mm/swap.c:mark_page_accessed
  - mm/memory.c:do_swap_page
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_vma
```
**Symbols:**

```
ffffffff812150d0-ffffffff8121518e: activate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void activate_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81224af0)
Location: mm/swap.c:306
Inline: False
Direct callers:
  - mm/swap.c:mark_page_accessed
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff81224af0-ffffffff81224ba9: activate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void activate_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81232880)
Location: mm/swap.c:307
Inline: False
Direct callers:
  - mm/swap.c:mark_page_accessed
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff81232880-ffffffff81232939: activate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void activate_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8125fdc0)
Location: mm/swap.c:351
Inline: False
Direct callers:
  - mm/swap.c:mark_page_accessed
  - mm/memory.c:do_swap_page
  - mm/swapfile.c:unuse_pte
```
**Symbols:**

```
ffffffff8125fdc0-ffffffff8125fe99: activate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void activate_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81269520)
Location: mm/swap.c:340
Inline: False
Direct callers:
  - mm/swap.c:mark_page_accessed
```
**Symbols:**

```
ffffffff81269520-ffffffff812695f7: activate_page (STB_LOCAL)
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
In mm/swap.c (ffffffff8126eafa)
Location: mm/swap.c:350
Inline: True
Inline callers:
  - mm/swap.c:mark_page_accessed
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
In mm/swap.c (ffffffff812abb4a)
Location: mm/swap.c:328
Inline: True
Inline callers:
  - mm/swap.c:mark_page_accessed
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
void activate_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffff8000102c2698)
Location: mm/swap.c:307
Inline: False
Direct callers:
  - mm/swap.c:mark_page_accessed
  - mm/memory.c:do_swap_page
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
ffff8000102c2698-ffff8000102c27a8: activate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void activate_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (c04ed8d8)
Location: mm/swap.c:307
Inline: False
Direct callers:
  - mm/swap.c:mark_page_accessed
  - mm/memory.c:do_swap_page
  - mm/swapfile.c:unuse_mm
```
**Symbols:**

```
c04ed8d8-c04ed9dc: activate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void activate_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (c00000000037c6a0)
Location: mm/swap.c:307
Inline: False
Direct callers:
  - mm/swap.c:mark_page_accessed
  - mm/memory.c:do_swap_page
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
c00000000037c6a0-c00000000037c818: activate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void activate_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffe0001e3a98)
Location: mm/swap.c:307
Inline: False
Direct callers:
  - mm/swap.c:mark_page_accessed
  - mm/memory.c:do_swap_page
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
ffffffe0001e3a98-ffffffe0001e3b88: activate_page (STB_GLOBAL)
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
void activate_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8122aed0)
Location: mm/swap.c:307
Inline: False
Direct callers:
  - mm/swap.c:mark_page_accessed
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff8122aed0-ffffffff8122af89: activate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void activate_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8121dfe0)
Location: mm/swap.c:307
Inline: False
Direct callers:
  - mm/swap.c:mark_page_accessed
  - mm/memory.c:do_swap_page
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
ffffffff8121dfe0-ffffffff8121e099: activate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void activate_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81228c70)
Location: mm/swap.c:307
Inline: False
Direct callers:
  - mm/swap.c:mark_page_accessed
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff81228c70-ffffffff81228d29: activate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void activate_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81237ff0)
Location: mm/swap.c:307
Inline: False
Direct callers:
  - mm/swap.c:mark_page_accessed
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff81237ff0-ffffffff812380c9: activate_page (STB_GLOBAL)
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
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
