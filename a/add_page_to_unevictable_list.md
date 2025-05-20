# Function: <code>add_page_to_unevictable_list</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void add_page_to_unevictable_list(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8119dec0)
Location: mm/swap.c:687
Inline: False
Direct callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/vmscan.c:putback_lru_page
```
**Symbols:**

```
ffffffff8119dec0-ffffffff8119dfae: add_page_to_unevictable_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void add_page_to_unevictable_list(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811b36e0)
Location: mm/swap.c:446
Inline: False
Direct callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/vmscan.c:putback_lru_page
```
**Symbols:**

```
ffffffff811b36e0-ffffffff811b382a: add_page_to_unevictable_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void add_page_to_unevictable_list(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811c3d60)
Location: mm/swap.c:447
Inline: False
Direct callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/vmscan.c:putback_lru_page
```
**Symbols:**

```
ffffffff811c3d60-ffffffff811c3eb1: add_page_to_unevictable_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void add_page_to_unevictable_list(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811cc150)
Location: mm/swap.c:458
Inline: False
Direct callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/vmscan.c:putback_lru_page
```
**Symbols:**

```
ffffffff811cc150-ffffffff811cc2a4: add_page_to_unevictable_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void add_page_to_unevictable_list(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811e1140)
Location: mm/swap.c:458
Inline: False
Direct callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/vmscan.c:putback_lru_page
```
**Symbols:**

```
ffffffff811e1140-ffffffff811e1294: add_page_to_unevictable_list (STB_GLOBAL)
```
</details>
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
</ul>
