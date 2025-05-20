# Function: <code>_swap_info_get</code>

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
struct swap_info_struct *_swap_info_get(swp_entry_t entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8120c7b0)
Location: mm/swapfile.c:1031
Inline: False
Direct callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:swap_free
```
**Symbols:**

```
ffffffff8120c7b0-ffffffff8120c7fb: _swap_info_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct swap_info_struct *_swap_info_get(swp_entry_t entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812264b0)
Location: mm/swapfile.c:1066
Inline: False
Direct callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:split_swap_cluster
  - mm/swapfile.c:swap_free
```
**Symbols:**

```
ffffffff812264b0-ffffffff812264fe: _swap_info_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct swap_info_struct *_swap_info_get(swp_entry_t entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:1066
Inline: False
Direct callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:split_swap_cluster
  - mm/swapfile.c:swap_free
```
**Symbols:**

```
ffffffff81248a40-ffffffff81248a78: _swap_info_get (STB_LOCAL)
ffffffff8124e6df-ffffffff8124e6fc: _swap_info_get.cold.50 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct swap_info_struct *_swap_info_get(swp_entry_t entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:1096
Inline: False
Direct callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:split_swap_cluster
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:swap_free
```
**Symbols:**

```
ffffffff8125d020-ffffffff8125d055: _swap_info_get (STB_LOCAL)
ffffffff81262bbf-ffffffff81262bdc: _swap_info_get.cold.50 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct swap_info_struct *_swap_info_get(swp_entry_t entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:1133
Inline: False
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:split_swap_cluster
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:swap_free
```
**Symbols:**

```
ffffffff81278280-ffffffff812782e9: _swap_info_get (STB_LOCAL)
ffffffff8127da6b-ffffffff8127dadf: _swap_info_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct swap_info_struct *_swap_info_get(swp_entry_t entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:1133
Inline: False
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:split_swap_cluster
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:swap_free
```
**Symbols:**

```
ffffffff81287d70-ffffffff81287dd9: _swap_info_get (STB_LOCAL)
ffffffff8128d50b-ffffffff8128d57f: _swap_info_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct swap_info_struct *_swap_info_get(swp_entry_t entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:1169
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:page_trans_huge_map_swapcount
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:split_swap_cluster
  - mm/swapfile.c:put_swap_page
```
**Symbols:**

```
ffffffff812ba130-ffffffff812ba19b: _swap_info_get (STB_LOCAL)
ffffffff812bffbf-ffffffff812c0033: _swap_info_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct swap_info_struct *_swap_info_get(swp_entry_t entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:1185
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:page_trans_huge_map_swapcount
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:split_swap_cluster
  - mm/swapfile.c:put_swap_page
```
**Symbols:**

```
ffffffff812c5ba0-ffffffff812c5c0b: _swap_info_get (STB_LOCAL)
ffffffff81be86e0-ffffffff81be8754: _swap_info_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct swap_info_struct *_swap_info_get(swp_entry_t entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:1184
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:page_trans_huge_map_swapcount
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:split_swap_cluster
  - mm/swapfile.c:put_swap_page
```
**Symbols:**

```
ffffffff812cc6b0-ffffffff812cc71b: _swap_info_get (STB_LOCAL)
ffffffff81bda6bb-ffffffff81bda74b: _swap_info_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct swap_info_struct *_swap_info_get(swp_entry_t entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:1153
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:page_trans_huge_map_swapcount
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:split_swap_cluster
  - mm/swapfile.c:put_swap_page
```
**Symbols:**

```
ffffffff813119f0-ffffffff81311a84: _swap_info_get (STB_LOCAL)
ffffffff81cbeb2a-ffffffff81cbebae: _swap_info_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct swap_info_struct *_swap_info_get(swp_entry_t entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:1128
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:try_to_free_swap
  - mm/swapfile.c:try_to_free_swap
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:split_swap_cluster
  - mm/swapfile.c:put_swap_page
```
**Symbols:**

```
ffffffff8137cb80-ffffffff8137cc2c: _swap_info_get (STB_LOCAL)
ffffffff81e70cbc-ffffffff81e70d31: _swap_info_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct swap_info_struct *_swap_info_get(swp_entry_t entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff813fa550)
Location: mm/swapfile.c:1132
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:folio_free_swap
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:split_swap_cluster
  - mm/swapfile.c:put_swap_folio
```
**Symbols:**

```
ffffffff813fa550-ffffffff813fa67b: _swap_info_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct swap_info_struct *_swap_info_get(swp_entry_t entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8142d490)
Location: mm/swapfile.c:1132
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:folio_free_swap
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:split_swap_cluster
  - mm/swapfile.c:put_swap_folio
```
**Symbols:**

```
ffffffff8142d490-ffffffff8142d5bb: _swap_info_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct swap_info_struct *_swap_info_get(swp_entry_t entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81466c00)
Location: mm/swapfile.c:1132
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:folio_free_swap
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:split_swap_cluster
  - mm/swapfile.c:put_swap_folio
```
**Symbols:**

```
ffffffff81466c00-ffffffff81466d2b: _swap_info_get (STB_LOCAL)
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
struct swap_info_struct *_swap_info_get(swp_entry_t entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffff800010322ba0)
Location: mm/swapfile.c:1133
Inline: False
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:swap_free
```
**Symbols:**

```
ffff800010322ba0-ffff800010322cb0: _swap_info_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct swap_info_struct *_swap_info_get(swp_entry_t entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c053af1c)
Location: mm/swapfile.c:1133
Inline: False
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:swap_free
```
**Symbols:**

```
c053af1c-c053b018: _swap_info_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct swap_info_struct *_swap_info_get(swp_entry_t entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c0000000003f8700)
Location: mm/swapfile.c:1133
Inline: False
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:swap_free
```
**Symbols:**

```
c0000000003f8700-c0000000003f8804: _swap_info_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct swap_info_struct *_swap_info_get(swp_entry_t entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffe000223750)
Location: mm/swapfile.c:1133
Inline: False
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:swap_free
```
**Symbols:**

```
ffffffe000223750-ffffffe000223838: _swap_info_get (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct swap_info_struct *_swap_info_get(swp_entry_t entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:1133
Inline: False
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:split_swap_cluster
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:swap_free
```
**Symbols:**

```
ffffffff81280350-ffffffff812803b9: _swap_info_get (STB_LOCAL)
ffffffff81285aeb-ffffffff81285b5f: _swap_info_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct swap_info_struct *_swap_info_get(swp_entry_t entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:1133
Inline: False
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:split_swap_cluster
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:swap_free
```
**Symbols:**

```
ffffffff812721c0-ffffffff81272229: _swap_info_get (STB_LOCAL)
ffffffff8127795b-ffffffff812779cf: _swap_info_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct swap_info_struct *_swap_info_get(swp_entry_t entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:1133
Inline: False
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:split_swap_cluster
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:swap_free
```
**Symbols:**

```
ffffffff8127e160-ffffffff8127e1c9: _swap_info_get (STB_LOCAL)
ffffffff812838fb-ffffffff8128396f: _swap_info_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct swap_info_struct *_swap_info_get(swp_entry_t entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:1133
Inline: False
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:split_swap_cluster
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:swap_free
```
**Symbols:**

```
ffffffff8128dd10-ffffffff8128dd79: _swap_info_get (STB_LOCAL)
ffffffff812935eb-ffffffff8129365f: _swap_info_get.cold (STB_LOCAL)
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
