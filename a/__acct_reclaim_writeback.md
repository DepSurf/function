# Function: <code>__acct_reclaim_writeback</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __acct_reclaim_writeback(pg_data_t *pgdat, struct folio *folio, int nr_throttled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81313300)
Location: mm/vmscan.c:1117
Inline: False
Direct callers:
  - mm/filemap.c:folio_end_writeback
```
**Symbols:**

```
ffffffff81313300-ffffffff813133c9: __acct_reclaim_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __acct_reclaim_writeback(pg_data_t *pgdat, struct folio *folio, int nr_throttled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81386770)
Location: mm/vmscan.c:1215
Inline: False
Direct callers:
  - mm/filemap.c:folio_end_writeback
```
**Symbols:**

```
ffffffff81386770-ffffffff8138680d: __acct_reclaim_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __acct_reclaim_writeback(pg_data_t *pgdat, struct folio *folio, int nr_throttled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813b6c00)
Location: mm/vmscan.c:1268
Inline: False
Direct callers:
  - mm/filemap.c:folio_end_writeback
```
**Symbols:**

```
ffffffff813b6c00-ffffffff813b6c9d: __acct_reclaim_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __acct_reclaim_writeback(pg_data_t *pgdat, struct folio *folio, int nr_throttled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813dfac0)
Location: mm/vmscan.c:567
Inline: False
Direct callers:
  - mm/filemap.c:folio_end_writeback
```
**Symbols:**

```
ffffffff813dfac0-ffffffff813dfb5a: __acct_reclaim_writeback (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
