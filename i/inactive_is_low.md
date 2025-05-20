# Function: <code>inactive_is_low</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool inactive_is_low(struct lruvec *lruvec, enum lru_list inactive_lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81263e00)
Location: mm/vmscan.c:2204
Inline: False
Direct callers:
  - mm/vmscan.c:age_active_anon
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_lruvec
```
**Symbols:**

```
ffffffff81263e00-ffffffff81263eab: inactive_is_low (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool inactive_is_low(struct lruvec *lruvec, enum lru_list inactive_lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8126e7a0)
Location: mm/vmscan.c:2211
Inline: False
Direct callers:
  - mm/vmscan.c:age_active_anon
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_lruvec
```
**Symbols:**

```
ffffffff8126e7a0-ffffffff8126e851: inactive_is_low (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool inactive_is_low(struct lruvec *lruvec, enum lru_list inactive_lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812737a0)
Location: mm/vmscan.c:2401
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_lruvec
```
**Symbols:**

```
ffffffff812737a0-ffffffff8127384b: inactive_is_low (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool inactive_is_low(struct lruvec *lruvec, enum lru_list inactive_lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812b0d40)
Location: mm/vmscan.c:2539
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_lruvec
  - mm/vmscan.c:shrink_lruvec
```
**Symbols:**

```
ffffffff812b0d40-ffffffff812b0e13: inactive_is_low (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool inactive_is_low(struct lruvec *lruvec, enum lru_list inactive_lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8130c360)
Location: mm/vmscan.c:2647
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_lruvec
  - mm/vmscan.c:shrink_lruvec
```
**Symbols:**

```
ffffffff8130c360-ffffffff8130c455: inactive_is_low (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool inactive_is_low(struct lruvec *lruvec, enum lru_list inactive_lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81378e30)
Location: mm/vmscan.c:2802
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:shrink_lruvec
  - mm/vmscan.c:prepare_scan_count
  - mm/vmscan.c:prepare_scan_count
```
**Symbols:**

```
ffffffff81378e30-ffffffff81378f29: inactive_is_low (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool inactive_is_low(struct lruvec *lruvec, enum lru_list inactive_lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813ad400)
Location: mm/vmscan.c:2886
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:shrink_lruvec
  - mm/vmscan.c:prepare_scan_count
  - mm/vmscan.c:prepare_scan_count
```
**Symbols:**

```
ffffffff813ad400-ffffffff813ad4f9: inactive_is_low (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool inactive_is_low(struct lruvec *lruvec, enum lru_list inactive_lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813d7540)
Location: mm/vmscan.c:2186
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:shrink_lruvec
  - mm/vmscan.c:prepare_scan_control
  - mm/vmscan.c:prepare_scan_control
```
**Symbols:**

```
ffffffff813d7540-ffffffff813d763b: inactive_is_low (STB_LOCAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
