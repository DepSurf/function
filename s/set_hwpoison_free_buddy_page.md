# Function: <code>set_hwpoison_free_buddy_page</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool set_hwpoison_free_buddy_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8120d3a0)
Location: mm/page_alloc.c:8382
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff8120d3a0-ffffffff8120d455: set_hwpoison_free_buddy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool set_hwpoison_free_buddy_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81273800)
Location: mm/page_alloc.c:8598
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff81273800-ffffffff812738b8: set_hwpoison_free_buddy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool set_hwpoison_free_buddy_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81282670)
Location: mm/page_alloc.c:8626
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff81282670-ffffffff81282728: set_hwpoison_free_buddy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool set_hwpoison_free_buddy_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812b47e0)
Location: mm/page_alloc.c:8763
Inline: False
Direct callers:
  - mm/migrate.c:unmap_and_move
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff812b47e0-ffffffff812b4891: set_hwpoison_free_buddy_page (STB_GLOBAL)
```
</details>
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
bool set_hwpoison_free_buddy_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff80001031aba8)
Location: mm/page_alloc.c:8626
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffff80001031aba8-ffff80001031ad34: set_hwpoison_free_buddy_page (STB_GLOBAL)
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
In mm/migrate.c (0)
Location: include/linux/page-flags.h:420
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool set_hwpoison_free_buddy_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003ee3b0)
Location: mm/page_alloc.c:8626
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
c0000000003ee3b0-c0000000003ee510: set_hwpoison_free_buddy_page (STB_GLOBAL)
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
In mm/migrate.c (0)
Location: include/linux/page-flags.h:420
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
bool set_hwpoison_free_buddy_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8127acc0)
Location: mm/page_alloc.c:8626
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff8127acc0-ffffffff8127ad78: set_hwpoison_free_buddy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool set_hwpoison_free_buddy_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8126cba0)
Location: mm/page_alloc.c:8626
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff8126cba0-ffffffff8126cc58: set_hwpoison_free_buddy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool set_hwpoison_free_buddy_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81278a60)
Location: mm/page_alloc.c:8626
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff81278a60-ffffffff81278b18: set_hwpoison_free_buddy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool set_hwpoison_free_buddy_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81288650)
Location: mm/page_alloc.c:8626
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff81288650-ffffffff81288708: set_hwpoison_free_buddy_page (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
