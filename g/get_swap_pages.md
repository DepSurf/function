# Function: <code>get_swap_pages</code>

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
int get_swap_pages(int n_goal, bool cluster, swp_entry_t *swp_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8120ee20)
Location: mm/swapfile.c:895
Inline: False
Direct callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
```
**Symbols:**

```
ffffffff8120ee20-ffffffff8120f119: get_swap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int get_swap_pages(int n_goal, bool cluster, swp_entry_t *swp_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8122a5f0)
Location: mm/swapfile.c:927
Inline: False
Direct callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
```
**Symbols:**

```
ffffffff8122a5f0-ffffffff8122a95d: get_swap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int get_swap_pages(int n_goal, bool cluster, swp_entry_t *swp_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8124b890)
Location: mm/swapfile.c:927
Inline: False
Direct callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
```
**Symbols:**

```
ffffffff8124b890-ffffffff8124bbfb: get_swap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int get_swap_pages(int n_goal, swp_entry_t *swp_entries, int entry_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8125ff20)
Location: mm/swapfile.c:957
Inline: False
Direct callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
```
**Symbols:**

```
ffffffff8125ff20-ffffffff81260275: get_swap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int get_swap_pages(int n_goal, swp_entry_t *swp_entries, int entry_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8127aba0)
Location: mm/swapfile.c:992
Inline: False
Direct callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
```
**Symbols:**

```
ffffffff8127aba0-ffffffff8127af18: get_swap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int get_swap_pages(int n_goal, swp_entry_t *swp_entries, int entry_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8128a680)
Location: mm/swapfile.c:992
Inline: False
Direct callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
```
**Symbols:**

```
ffffffff8128a680-ffffffff8128a9f8: get_swap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int get_swap_pages(int n_goal, swp_entry_t *swp_entries, int entry_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812bd450)
Location: mm/swapfile.c:1032
Inline: False
Direct callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
```
**Symbols:**

```
ffffffff812bd450-ffffffff812bd71e: get_swap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int get_swap_pages(int n_goal, swp_entry_t *swp_entries, int entry_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812c8f70)
Location: mm/swapfile.c:1047
Inline: False
Direct callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
```
**Symbols:**

```
ffffffff812c8f70-ffffffff812c9245: get_swap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int get_swap_pages(int n_goal, swp_entry_t *swp_entries, int entry_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812cf9f0)
Location: mm/swapfile.c:1046
Inline: False
Direct callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
```
**Symbols:**

```
ffffffff812cf9f0-ffffffff812cfdcb: get_swap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int get_swap_pages(int n_goal, swp_entry_t *swp_entries, int entry_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81314fc0)
Location: mm/swapfile.c:1039
Inline: False
Direct callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
```
**Symbols:**

```
ffffffff81314fc0-ffffffff8131539d: get_swap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int get_swap_pages(int n_goal, swp_entry_t *swp_entries, int entry_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81380530)
Location: mm/swapfile.c:1043
Inline: False
Direct callers:
  - mm/swap_slots.c:folio_alloc_swap
  - mm/swap_slots.c:folio_alloc_swap
```
**Symbols:**

```
ffffffff81380530-ffffffff81380942: get_swap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int get_swap_pages(int n_goal, swp_entry_t *swp_entries, int entry_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff813fee20)
Location: mm/swapfile.c:1046
Inline: False
Direct callers:
  - mm/swap_slots.c:folio_alloc_swap
  - mm/swap_slots.c:folio_alloc_swap
```
**Symbols:**

```
ffffffff813fee20-ffffffff813ff237: get_swap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int get_swap_pages(int n_goal, swp_entry_t *swp_entries, int entry_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81431d60)
Location: mm/swapfile.c:1048
Inline: False
Direct callers:
  - mm/swap_slots.c:folio_alloc_swap
  - mm/swap_slots.c:folio_alloc_swap
```
**Symbols:**

```
ffffffff81431d60-ffffffff8143215c: get_swap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int get_swap_pages(int n_goal, swp_entry_t *swp_entries, int entry_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8146b150)
Location: mm/swapfile.c:1048
Inline: False
Direct callers:
  - mm/swap_slots.c:folio_alloc_swap
  - mm/swap_slots.c:folio_alloc_swap
```
**Symbols:**

```
ffffffff8146b150-ffffffff8146b54c: get_swap_pages (STB_GLOBAL)
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
int get_swap_pages(int n_goal, swp_entry_t *swp_entries, int entry_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffff800010325820)
Location: mm/swapfile.c:992
Inline: False
Direct callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
```
**Symbols:**

```
ffff800010325820-ffff800010325bd8: get_swap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int get_swap_pages(int n_goal, swp_entry_t *swp_entries, int entry_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c053d0c8)
Location: mm/swapfile.c:992
Inline: False
Direct callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
```
**Symbols:**

```
c053d0c8-c053d34c: get_swap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int get_swap_pages(int n_goal, swp_entry_t *swp_entries, int entry_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c0000000003fbaf0)
Location: mm/swapfile.c:992
Inline: False
Direct callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
```
**Symbols:**

```
c0000000003fbaf0-c0000000003fbf08: get_swap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int get_swap_pages(int n_goal, swp_entry_t *swp_entries, int entry_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffe000225d52)
Location: mm/swapfile.c:992
Inline: False
Direct callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
```
**Symbols:**

```
ffffffe000225d52-ffffffe000226020: get_swap_pages (STB_GLOBAL)
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
int get_swap_pages(int n_goal, swp_entry_t *swp_entries, int entry_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81282c60)
Location: mm/swapfile.c:992
Inline: False
Direct callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
```
**Symbols:**

```
ffffffff81282c60-ffffffff81282fd8: get_swap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int get_swap_pages(int n_goal, swp_entry_t *swp_entries, int entry_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81274780)
Location: mm/swapfile.c:992
Inline: False
Direct callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
```
**Symbols:**

```
ffffffff81274780-ffffffff81274af8: get_swap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int get_swap_pages(int n_goal, swp_entry_t *swp_entries, int entry_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81280a70)
Location: mm/swapfile.c:992
Inline: False
Direct callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
```
**Symbols:**

```
ffffffff81280a70-ffffffff81280de8: get_swap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int get_swap_pages(int n_goal, swp_entry_t *swp_entries, int entry_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81290790)
Location: mm/swapfile.c:992
Inline: False
Direct callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
```
**Symbols:**

```
ffffffff81290790-ffffffff81290af9: get_swap_pages (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int entry_size</code>
</li>
<li>
<b>Param removed. </b>
<code>bool cluster</code>
</li>
<li>
<b>Param reordered. </b>
<code>n_goal, cluster, swp_entries</code> ➡️ <code>n_goal, swp_entries, entry_size</code>
</li>
</ul>
</details>
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
