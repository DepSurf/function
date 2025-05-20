# Function: <code>try_to_unmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int try_to_unmap(struct page *page, enum ttu_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811cc400)
Location: mm/rmap.c:1472
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff811cc400-ffffffff811cc4a2: try_to_unmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int try_to_unmap(struct page *page, enum ttu_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811e9440)
Location: mm/rmap.c:1629
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff811e9440-ffffffff811e956e: try_to_unmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int try_to_unmap(struct page *page, enum ttu_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811fa790)
Location: mm/rmap.c:1628
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff811fa790-ffffffff811fa8be: try_to_unmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool try_to_unmap(struct page *page, enum ttu_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81205470)
Location: mm/rmap.c:1561
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff81205470-ffffffff81205552: try_to_unmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool try_to_unmap(struct page *page, enum ttu_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8121e420)
Location: mm/rmap.c:1645
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff8121e420-ffffffff8121e504: try_to_unmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool try_to_unmap(struct page *page, enum ttu_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812402e0)
Location: mm/rmap.c:1663
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff812402e0-ffffffff812403c8: try_to_unmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool try_to_unmap(struct page *page, enum ttu_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812549e0)
Location: mm/rmap.c:1698
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/memory_hotplug.c:__offline_pages
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff812549e0-ffffffff81254acc: try_to_unmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool try_to_unmap(struct page *page, enum ttu_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81266c90)
Location: mm/rmap.c:1708
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/memory_hotplug.c:do_migrate_range
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff81266c90-ffffffff81266d85: try_to_unmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool try_to_unmap(struct page *page, enum ttu_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812755b0)
Location: mm/rmap.c:1708
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/memory_hotplug.c:do_migrate_range
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff812755b0-ffffffff812756a5: try_to_unmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool try_to_unmap(struct page *page, enum ttu_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812a6930)
Location: mm/rmap.c:1746
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/migrate.c:migrate_vma_unmap
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:__unmap_and_move
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff812a6930-ffffffff812a6a53: try_to_unmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool try_to_unmap(struct page *page, enum ttu_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812b1dd0)
Location: mm/rmap.c:1740
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/migrate.c:migrate_vma_unmap
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:__unmap_and_move
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff812b1dd0-ffffffff812b1ef3: try_to_unmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool try_to_unmap(struct page *page, enum ttu_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812b74a0)
Location: mm/rmap.c:1761
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/migrate.c:migrate_vma_unmap
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:__unmap_and_move
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff812b74a0-ffffffff812b75c3: try_to_unmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void try_to_unmap(struct page *page, enum ttu_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812f9b40)
Location: mm/rmap.c:1672
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
```
**Symbols:**

```
ffffffff812f9b40-ffffffff812f9bd5: try_to_unmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void try_to_unmap(struct folio *folio, enum ttu_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8135f440)
Location: mm/rmap.c:1815
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/khugepaged.c:collapse_file
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
```
**Symbols:**

```
ffffffff8135f440-ffffffff8135f4f2: try_to_unmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void try_to_unmap(struct folio *folio, enum ttu_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff813da270)
Location: mm/rmap.c:1812
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_folio_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/khugepaged.c:collapse_file
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
```
**Symbols:**

```
ffffffff813da270-ffffffff813da322: try_to_unmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void try_to_unmap(struct folio *folio, enum ttu_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8140e9b0)
Location: mm/rmap.c:1792
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_folio_list
  - mm/memory_hotplug.c:do_migrate_range
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/khugepaged.c:collapse_file
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
```
**Symbols:**

```
ffffffff8140e9b0-ffffffff8140ea61: try_to_unmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void try_to_unmap(struct folio *folio, enum ttu_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8143b370)
Location: mm/rmap.c:1944
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_folio_list
  - mm/memory_hotplug.c:do_migrate_range
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/khugepaged.c:collapse_file
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
```
**Symbols:**

```
ffffffff8143b370-ffffffff8143b421: try_to_unmap (STB_GLOBAL)
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
bool try_to_unmap(struct page *page, enum ttu_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffff80001030b508)
Location: mm/rmap.c:1708
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffff80001030b508-ffff80001030b634: try_to_unmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool try_to_unmap(struct page *page, enum ttu_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (c0527968)
Location: mm/rmap.c:1708
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/migrate.c:migrate_pages
```
**Symbols:**

```
c0527968-c0527a94: try_to_unmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool try_to_unmap(struct page *page, enum ttu_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (c0000000003db650)
Location: mm/rmap.c:1708
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/memory_hotplug.c:do_migrate_range
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
c0000000003db650-c0000000003db7c0: try_to_unmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool try_to_unmap(struct page *page, enum ttu_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffe000214eb4)
Location: mm/rmap.c:1708
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/migrate.c:migrate_pages
```
**Symbols:**

```
ffffffe000214eb4-ffffffe000214faa: try_to_unmap (STB_GLOBAL)
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
bool try_to_unmap(struct page *page, enum ttu_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8126dc00)
Location: mm/rmap.c:1708
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/memory_hotplug.c:do_migrate_range
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff8126dc00-ffffffff8126dcf5: try_to_unmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool try_to_unmap(struct page *page, enum ttu_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8125fc30)
Location: mm/rmap.c:1708
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/memory_hotplug.c:do_migrate_range
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff8125fc30-ffffffff8125fd25: try_to_unmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool try_to_unmap(struct page *page, enum ttu_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8126b9a0)
Location: mm/rmap.c:1708
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/memory_hotplug.c:do_migrate_range
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff8126b9a0-ffffffff8126ba95: try_to_unmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool try_to_unmap(struct page *page, enum ttu_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8127b330)
Location: mm/rmap.c:1708
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/memory_hotplug.c:do_migrate_range
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff8127b330-ffffffff8127b425: try_to_unmap (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio *folio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *page</code>
</li>
</ul>
</details>
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
