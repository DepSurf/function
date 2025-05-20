# Function: <code>page_cache_ra_unbounded</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void page_cache_ra_unbounded(struct readahead_control *ractl, long unsigned int nr_to_read, long unsigned int lookahead_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff81267160)
Location: mm/readahead.c:174
Inline: False
Direct callers:
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_ra
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
```
**Symbols:**

```
ffffffff81267160-ffffffff81267348: page_cache_ra_unbounded (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void page_cache_ra_unbounded(struct readahead_control *ractl, long unsigned int nr_to_read, long unsigned int lookahead_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff8126bdb0)
Location: mm/readahead.c:174
Inline: False
Direct callers:
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_ra
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
```
**Symbols:**

```
ffffffff8126bdb0-ffffffff8126bf9a: page_cache_ra_unbounded (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void page_cache_ra_unbounded(struct readahead_control *ractl, long unsigned int nr_to_read, long unsigned int lookahead_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff812a8a70)
Location: mm/readahead.c:174
Inline: False
Direct callers:
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_ra
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
```
**Symbols:**

```
ffffffff812a8a70-ffffffff812a8c7a: page_cache_ra_unbounded (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void page_cache_ra_unbounded(struct readahead_control *ractl, long unsigned int nr_to_read, long unsigned int lookahead_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff81301730)
Location: mm/readahead.c:200
Inline: False
Direct callers:
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:force_page_cache_ra
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
```
**Symbols:**

```
ffffffff81301730-ffffffff813018b4: page_cache_ra_unbounded (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void page_cache_ra_unbounded(struct readahead_control *ractl, long unsigned int nr_to_read, long unsigned int lookahead_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/readahead.c (0)
Location: mm/readahead.c:206
Inline: False
Direct callers:
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:force_page_cache_ra
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
```
**Symbols:**

```
ffffffff820624d1-ffffffff820624ed: page_cache_ra_unbounded.cold (STB_LOCAL)
ffffffff8136bdb0-ffffffff8136bf72: page_cache_ra_unbounded (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void page_cache_ra_unbounded(struct readahead_control *ractl, long unsigned int nr_to_read, long unsigned int lookahead_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/readahead.c (0)
Location: mm/readahead.c:205
Inline: False
Direct callers:
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:force_page_cache_ra
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
```
**Symbols:**

```
ffffffff820e1cac-ffffffff820e1cc8: page_cache_ra_unbounded.cold (STB_LOCAL)
ffffffff8139e040-ffffffff8139e1fe: page_cache_ra_unbounded (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void page_cache_ra_unbounded(struct readahead_control *ractl, long unsigned int nr_to_read, long unsigned int lookahead_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/readahead.c (0)
Location: mm/readahead.c:205
Inline: False
Direct callers:
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:force_page_cache_ra
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
```
**Symbols:**

```
ffffffff821be6d1-ffffffff821be6ed: page_cache_ra_unbounded.cold (STB_LOCAL)
ffffffff813c7ce0-ffffffff813c7e9e: page_cache_ra_unbounded (STB_GLOBAL)
```
</details>
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
