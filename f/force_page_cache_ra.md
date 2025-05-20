# Function: <code>force_page_cache_ra</code>

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
void force_page_cache_ra(struct readahead_control *ractl, struct file_ra_state *ra, long unsigned int nr_to_read);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff812677c0)
Location: mm/readahead.c:274
Inline: False
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/readahead.c:page_cache_sync_ra
```
**Symbols:**

```
ffffffff812677c0-ffffffff812678f9: force_page_cache_ra (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void force_page_cache_ra(struct readahead_control *ractl, long unsigned int nr_to_read);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff8126c3d0)
Location: mm/readahead.c:274
Inline: False
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/readahead.c:page_cache_sync_ra
```
**Symbols:**

```
ffffffff8126c3d0-ffffffff8126c50f: force_page_cache_ra (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void force_page_cache_ra(struct readahead_control *ractl, long unsigned int nr_to_read);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff812a90e0)
Location: mm/readahead.c:276
Inline: False
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/readahead.c:page_cache_sync_ra
```
**Symbols:**

```
ffffffff812a90e0-ffffffff812a9229: force_page_cache_ra (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void force_page_cache_ra(struct readahead_control *ractl, long unsigned int nr_to_read);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff81301ad0)
Location: mm/readahead.c:300
Inline: False
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/readahead.c:page_cache_sync_ra
```
**Symbols:**

```
ffffffff81301ad0-ffffffff81301b98: force_page_cache_ra (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void force_page_cache_ra(struct readahead_control *ractl, long unsigned int nr_to_read);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff8136c230)
Location: mm/readahead.c:307
Inline: False
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/readahead.c:page_cache_sync_ra
```
**Symbols:**

```
ffffffff8136c230-ffffffff8136c2f8: force_page_cache_ra (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void force_page_cache_ra(struct readahead_control *ractl, long unsigned int nr_to_read);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff8139e440)
Location: mm/readahead.c:306
Inline: False
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/readahead.c:page_cache_sync_ra
```
**Symbols:**

```
ffffffff8139e440-ffffffff8139e505: force_page_cache_ra (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void force_page_cache_ra(struct readahead_control *ractl, long unsigned int nr_to_read);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff813c80e0)
Location: mm/readahead.c:306
Inline: False
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/readahead.c:page_cache_sync_ra
```
**Symbols:**

```
ffffffff813c80e0-ffffffff813c81a5: force_page_cache_ra (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct file_ra_state *ra</code>
</li>
<li>
<b>Param reordered. </b>
<code>ractl, ra, nr_to_read</code> ➡️ <code>ractl, nr_to_read</code>
</li>
</ul>
</details>
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
