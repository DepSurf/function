# Function: <code>get_swappiness</code>

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
int get_swappiness(struct lruvec *lruvec, struct scan_control *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8137f300)
Location: mm/vmscan.c:3203
Inline: False
Direct callers:
  - mm/vmscan.c:run_cmd
  - mm/vmscan.c:lru_gen_shrink_lruvec
  - mm/vmscan.c:lru_gen_shrink_lruvec
  - mm/vmscan.c:lru_gen_age_node
```
**Symbols:**

```
ffffffff8137f300-ffffffff8137f36b: get_swappiness (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int get_swappiness(struct lruvec *lruvec, struct scan_control *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813b2f00)
Location: mm/vmscan.c:3300
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:run_cmd
  - mm/vmscan.c:try_to_shrink_lruvec
  - mm/vmscan.c:lruvec_is_sizable
```
**Symbols:**

```
ffffffff813b2f00-ffffffff813b2f85: get_swappiness (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int get_swappiness(struct lruvec *lruvec, struct scan_control *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813dc4f0)
Location: mm/vmscan.c:2600
Inline: False
Direct callers:
  - mm/vmscan.c:run_cmd
  - mm/vmscan.c:lru_gen_shrink_node
  - mm/vmscan.c:try_to_shrink_lruvec
  - mm/vmscan.c:lruvec_is_sizable
```
**Symbols:**

```
ffffffff813dc4f0-ffffffff813dc575: get_swappiness (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
