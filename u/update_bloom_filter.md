# Function: <code>update_bloom_filter</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void update_bloom_filter(struct lruvec *lruvec, long unsigned int seq, void *item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813736f0)
Location: mm/vmscan.c:3402
Inline: False
Direct callers:
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:walk_pmd_range
```
**Symbols:**

```
ffffffff813736f0-ffffffff81373752: update_bloom_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void update_bloom_filter(struct lruvec *lruvec, long unsigned int seq, void *item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813a5a60)
Location: mm/vmscan.c:3386
Inline: False
Direct callers:
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:walk_pmd_range
```
**Symbols:**

```
ffffffff813a5a60-ffffffff813a5ac2: update_bloom_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void update_bloom_filter(struct lru_gen_mm_state *mm_state, long unsigned int seq, void *item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813cf5e0)
Location: mm/vmscan.c:2687
Inline: False
Direct callers:
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:walk_pmd_range
```
**Symbols:**

```
ffffffff813cf5e0-ffffffff813cf63f: update_bloom_filter (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct lru_gen_mm_state *mm_state</code>
</li>
<li>
<b>Param removed. </b>
<code>struct lruvec *lruvec</code>
</li>
</ul>
</details>
</li>
</ul>
