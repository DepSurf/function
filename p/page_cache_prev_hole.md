# Function: <code>page_cache_prev_hole</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int page_cache_prev_hole(struct address_space *mapping, long unsigned int index, long unsigned int max_scan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8118cf20)
Location: mm/filemap.c:997
Inline: False
Direct callers:
  - mm/readahead.c:ondemand_readahead
```
**Symbols:**

```
ffffffff8118cf20-ffffffff8118cf6f: page_cache_prev_hole (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int page_cache_prev_hole(struct address_space *mapping, long unsigned int index, long unsigned int max_scan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8119fed0)
Location: mm/filemap.c:1040
Inline: False
Direct callers:
  - mm/readahead.c:ondemand_readahead
```
**Symbols:**

```
ffffffff8119fed0-ffffffff8119ff1f: page_cache_prev_hole (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int page_cache_prev_hole(struct address_space *mapping, long unsigned int index, long unsigned int max_scan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811af4d0)
Location: mm/filemap.c:1142
Inline: False
Direct callers:
  - mm/readahead.c:ondemand_readahead
```
**Symbols:**

```
ffffffff811af4d0-ffffffff811af51f: page_cache_prev_hole (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int page_cache_prev_hole(struct address_space *mapping, long unsigned int index, long unsigned int max_scan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b63d0)
Location: mm/filemap.c:1268
Inline: False
Direct callers:
  - mm/readahead.c:ondemand_readahead
```
**Symbols:**

```
ffffffff811b63d0-ffffffff811b641f: page_cache_prev_hole (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int page_cache_prev_hole(struct address_space *mapping, long unsigned int index, long unsigned int max_scan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ca6e0)
Location: mm/filemap.c:1390
Inline: False
Direct callers:
  - mm/readahead.c:ondemand_readahead
```
**Symbols:**

```
ffffffff811ca6e0-ffffffff811ca72f: page_cache_prev_hole (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int page_cache_prev_hole(struct address_space *mapping, long unsigned int index, long unsigned int max_scan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811eb790)
Location: mm/filemap.c:1390
Inline: False
Direct callers:
  - mm/readahead.c:ondemand_readahead
```
**Symbols:**

```
ffffffff811eb790-ffffffff811eb7df: page_cache_prev_hole (STB_GLOBAL)
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
