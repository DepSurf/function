# Function: <code>page_cache_next_hole</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int page_cache_next_hole(struct address_space *mapping, long unsigned int index, long unsigned int max_scan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8118ced0)
Location: mm/filemap.c:956
Inline: False
Direct callers:
  - mm/readahead.c:ondemand_readahead
```
**Symbols:**

```
ffffffff8118ced0-ffffffff8118cf19: page_cache_next_hole (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int page_cache_next_hole(struct address_space *mapping, long unsigned int index, long unsigned int max_scan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8119fe80)
Location: mm/filemap.c:999
Inline: False
Direct callers:
  - mm/readahead.c:ondemand_readahead
```
**Symbols:**

```
ffffffff8119fe80-ffffffff8119fec9: page_cache_next_hole (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int page_cache_next_hole(struct address_space *mapping, long unsigned int index, long unsigned int max_scan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811af480)
Location: mm/filemap.c:1101
Inline: False
Direct callers:
  - mm/readahead.c:ondemand_readahead
```
**Symbols:**

```
ffffffff811af480-ffffffff811af4c9: page_cache_next_hole (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int page_cache_next_hole(struct address_space *mapping, long unsigned int index, long unsigned int max_scan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b6380)
Location: mm/filemap.c:1227
Inline: False
Direct callers:
  - mm/readahead.c:ondemand_readahead
```
**Symbols:**

```
ffffffff811b6380-ffffffff811b63c9: page_cache_next_hole (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int page_cache_next_hole(struct address_space *mapping, long unsigned int index, long unsigned int max_scan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ca690)
Location: mm/filemap.c:1349
Inline: False
Direct callers:
  - mm/readahead.c:ondemand_readahead
```
**Symbols:**

```
ffffffff811ca690-ffffffff811ca6d9: page_cache_next_hole (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int page_cache_next_hole(struct address_space *mapping, long unsigned int index, long unsigned int max_scan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811eb740)
Location: mm/filemap.c:1349
Inline: False
Direct callers:
  - mm/readahead.c:ondemand_readahead
```
**Symbols:**

```
ffffffff811eb740-ffffffff811eb789: page_cache_next_hole (STB_GLOBAL)
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
