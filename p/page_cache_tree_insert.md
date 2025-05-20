# Function: <code>page_cache_tree_insert</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8118dd59)
Location: mm/filemap.c:565
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int page_cache_tree_insert(struct address_space *mapping, struct page *page, void **shadowp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8119f7a0)
Location: mm/filemap.c:113
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
```
**Symbols:**

```
ffffffff8119f7a0-ffffffff8119f8f9: page_cache_tree_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int page_cache_tree_insert(struct address_space *mapping, struct page *page, void **shadowp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811af1c0)
Location: mm/filemap.c:113
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
```
**Symbols:**

```
ffffffff811af1c0-ffffffff811af2d8: page_cache_tree_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int page_cache_tree_insert(struct address_space *mapping, struct page *page, void **shadowp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b6120)
Location: mm/filemap.c:114
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
```
**Symbols:**

```
ffffffff811b6120-ffffffff811b61d4: page_cache_tree_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int page_cache_tree_insert(struct address_space *mapping, struct page *page, void **shadowp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ca3d0)
Location: mm/filemap.c:115
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
```
**Symbols:**

```
ffffffff811ca3d0-ffffffff811ca4ab: page_cache_tree_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int page_cache_tree_insert(struct address_space *mapping, struct page *page, void **shadowp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811eb480)
Location: mm/filemap.c:114
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
```
**Symbols:**

```
ffffffff811eb480-ffffffff811eb55b: page_cache_tree_insert (STB_LOCAL)
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
