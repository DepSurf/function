# Function: <code>reclaim_throttle</code>

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
void reclaim_throttle(pg_data_t *pgdat, enum vmscan_throttle_state reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81310bf0)
Location: mm/vmscan.c:1043
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_inactive_list
  - mm/compaction.c:isolate_migratepages_block
```
**Symbols:**

```
ffffffff81310bf0-ffffffff81310f31: reclaim_throttle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void reclaim_throttle(pg_data_t *pgdat, enum vmscan_throttle_state reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813840c0)
Location: mm/vmscan.c:1141
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/compaction.c:isolate_migratepages_block
```
**Symbols:**

```
ffffffff813840c0-ffffffff81384417: reclaim_throttle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void reclaim_throttle(pg_data_t *pgdat, enum vmscan_throttle_state reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813b5b60)
Location: mm/vmscan.c:1194
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/compaction.c:isolate_migratepages_block
```
**Symbols:**

```
ffffffff813b5b60-ffffffff813b5eb9: reclaim_throttle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void reclaim_throttle(pg_data_t *pgdat, enum vmscan_throttle_state reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813dea20)
Location: mm/vmscan.c:493
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/compaction.c:isolate_migratepages_block
```
**Symbols:**

```
ffffffff813dea20-ffffffff813ded79: reclaim_throttle (STB_GLOBAL)
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
