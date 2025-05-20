# Function: <code>__add_to_swap_cache</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __add_to_swap_cache(struct page *page, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff811d2710)
Location: mm/swap_state.c:79
Inline: False
Direct callers:
  - mm/swap_state.c:add_to_swap
  - mm/swap_state.c:__read_swap_cache_async
```
**Symbols:**

```
ffffffff811d2710-ffffffff811d27f0: __add_to_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __add_to_swap_cache(struct page *page, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff811f0380)
Location: mm/swap_state.c:79
Inline: False
Direct callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:add_to_swap
```
**Symbols:**

```
ffffffff811f0380-ffffffff811f04b4: __add_to_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __add_to_swap_cache(struct page *page, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff81200d30)
Location: mm/swap_state.c:81
Inline: False
Direct callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:add_to_swap
```
**Symbols:**

```
ffffffff81200d30-ffffffff81200e71: __add_to_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __add_to_swap_cache(struct page *page, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8120ba60)
Location: mm/swap_state.c:93
Inline: False
Direct callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:add_to_swap_cache
```
**Symbols:**

```
ffffffff8120ba60-ffffffff8120bc59: __add_to_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __add_to_swap_cache(struct page *page, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff81225050)
Location: mm/swap_state.c:113
Inline: False
Direct callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:add_to_swap_cache
```
**Symbols:**

```
ffffffff81225050-ffffffff8122524b: __add_to_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __add_to_swap_cache(struct page *page, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff81247610)
Location: mm/swap_state.c:113
Inline: False
Direct callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:add_to_swap_cache
```
**Symbols:**

```
ffffffff81247610-ffffffff812477e8: __add_to_swap_cache (STB_GLOBAL)
```
</details>
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
</ul>
