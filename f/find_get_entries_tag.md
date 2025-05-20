# Function: <code>find_get_entries_tag</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int find_get_entries_tag(struct address_space *mapping, long unsigned int start, int tag, unsigned int nr_entries, struct page **entries, long unsigned int *indices);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811a0900)
Location: mm/filemap.c:1571
Inline: True
```
**Symbols:**

```
ffffffff811a0900-ffffffff811a0bb6: find_get_entries_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
unsigned int find_get_entries_tag(struct address_space *mapping, long unsigned int start, int tag, unsigned int nr_entries, struct page **entries, long unsigned int *indices);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b0560)
Location: mm/filemap.c:1673
Inline: True
```
**Symbols:**

```
ffffffff811b0560-ffffffff811b07ba: find_get_entries_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
unsigned int find_get_entries_tag(struct address_space *mapping, long unsigned int start, int tag, unsigned int nr_entries, struct page **entries, long unsigned int *indices);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b6ed0)
Location: mm/filemap.c:1801
Inline: True
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
```
**Symbols:**

```
ffffffff811b6ed0-ffffffff811b70da: find_get_entries_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
unsigned int find_get_entries_tag(struct address_space *mapping, long unsigned int start, int tag, unsigned int nr_entries, struct page **entries, long unsigned int *indices);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811cb880)
Location: mm/filemap.c:1961
Inline: True
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
```
**Symbols:**

```
ffffffff811cb880-ffffffff811cbab5: find_get_entries_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
unsigned int find_get_entries_tag(struct address_space *mapping, long unsigned int start, int tag, unsigned int nr_entries, struct page **entries, long unsigned int *indices);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ec6b0)
Location: mm/filemap.c:1959
Inline: True
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
```
**Symbols:**

```
ffffffff811ec6b0-ffffffff811ec8cb: find_get_entries_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int find_get_entries_tag(struct address_space *mapping, long unsigned int start, xa_mark_t tag, unsigned int nr_entries, struct page **entries, long unsigned int *indices);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811fde10)
Location: mm/filemap.c:1953
Inline: False
```
**Symbols:**

```
ffffffff811fde10-ffffffff811fe0a9: find_get_entries_tag (STB_GLOBAL)
```
</details>
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
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int tag</code> ➡️ <code>xa_mark_t tag</code>
</li>
</ul>
</details>
</li>
</ul>
