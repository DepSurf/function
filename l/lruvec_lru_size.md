# Function: <code>lruvec_lru_size</code>

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
long unsigned int lruvec_lru_size(struct lruvec *lruvec, enum lru_list lru);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811b8710)
Location: mm/vmscan.c:237
Inline: True
Direct callers:
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:inactive_list_is_low
  - mm/workingset.c:workingset_refault
```
**Symbols:**

```
ffffffff811b8710-ffffffff811b8734: lruvec_lru_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int lruvec_lru_size(struct lruvec *lruvec, enum lru_list lru, int zone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811c8d30)
Location: mm/vmscan.c:243
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:inactive_list_is_low
  - mm/workingset.c:workingset_refault
```
**Symbols:**

```
ffffffff811c8d30-ffffffff811c8e04: lruvec_lru_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int lruvec_lru_size(struct lruvec *lruvec, enum lru_list lru, int zone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811d1670)
Location: mm/vmscan.c:244
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:inactive_list_is_low
  - mm/workingset.c:workingset_refault
```
**Symbols:**

```
ffffffff811d1670-ffffffff811d1775: lruvec_lru_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int lruvec_lru_size(struct lruvec *lruvec, enum lru_list lru, int zone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811e6b10)
Location: mm/vmscan.c:245
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:inactive_list_is_low
  - mm/workingset.c:workingset_refault
```
**Symbols:**

```
ffffffff811e6b10-ffffffff811e6c15: lruvec_lru_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int lruvec_lru_size(struct lruvec *lruvec, enum lru_list lru, int zone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81207ed0)
Location: mm/vmscan.c:274
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:inactive_list_is_low
  - mm/workingset.c:workingset_refault
```
**Symbols:**

```
ffffffff81207ed0-ffffffff81207fce: lruvec_lru_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int lruvec_lru_size(struct lruvec *lruvec, enum lru_list lru, int zone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8121aa50)
Location: mm/vmscan.c:343
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:inactive_list_is_low
  - mm/workingset.c:workingset_refault
```
**Symbols:**

```
ffffffff8121aa50-ffffffff8121ab4f: lruvec_lru_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int lruvec_lru_size(struct lruvec *lruvec, enum lru_list lru, int zone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8122a2b0)
Location: mm/vmscan.c:355
Inline: False
Direct callers:
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:inactive_list_is_low
  - mm/workingset.c:workingset_refault
```
**Symbols:**

```
ffffffff8122a2b0-ffffffff8122a3ea: lruvec_lru_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int lruvec_lru_size(struct lruvec *lruvec, enum lru_list lru, int zone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81238130)
Location: mm/vmscan.c:352
Inline: False
Direct callers:
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:inactive_list_is_low
  - mm/workingset.c:workingset_refault
```
**Symbols:**

```
ffffffff81238130-ffffffff8123822e: lruvec_lru_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int lruvec_lru_size(struct lruvec *lruvec, enum lru_list lru, int zone_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812641da)
Location: mm/vmscan.c:320
Inline: True
Inline callers:
  - mm/vmscan.c:get_scan_count
```
**Symbols:**

```
ffffffff81267160-ffffffff812671e4: lruvec_lru_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long unsigned int lruvec_lru_size(struct lruvec *lruvec, enum lru_list lru, int zone_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8126ebc2)
Location: mm/vmscan.c:313
Inline: True
Inline callers:
  - mm/vmscan.c:get_scan_count
```
**Symbols:**

```
ffffffff81271bb0-ffffffff81271c39: lruvec_lru_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81273cff)
Location: mm/vmscan.c:545
Inline: True
Inline callers:
  - mm/vmscan.c:get_scan_count
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812b1819)
Location: mm/vmscan.c:591
Inline: True
Inline callers:
  - mm/vmscan.c:get_scan_count
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8130c71e)
Location: mm/vmscan.c:588
Inline: True
Inline callers:
  - mm/vmscan.c:get_scan_count
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81381b0e)
Location: mm/vmscan.c:602
Inline: True
Inline callers:
  - mm/vmscan.c:get_scan_count
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813b33d5)
Location: mm/vmscan.c:654
Inline: True
Inline callers:
  - mm/vmscan.c:get_scan_count
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813dc9c5)
Location: mm/vmscan.c:360
Inline: True
Inline callers:
  - mm/vmscan.c:get_scan_count
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
long unsigned int lruvec_lru_size(struct lruvec *lruvec, enum lru_list lru, int zone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffff8000102c8eb8)
Location: mm/vmscan.c:352
Inline: False
Direct callers:
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/workingset.c:workingset_refault
```
**Symbols:**

```
ffff8000102c8eb8-ffff8000102c8fac: lruvec_lru_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int lruvec_lru_size(struct lruvec *lruvec, enum lru_list lru, int zone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c04f2dfc)
Location: mm/vmscan.c:352
Inline: False
Direct callers:
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:inactive_list_is_low
  - mm/workingset.c:workingset_refault
```
**Symbols:**

```
c04f2dfc-c04f2eb8: lruvec_lru_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int lruvec_lru_size(struct lruvec *lruvec, enum lru_list lru, int zone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c0000000003851d0)
Location: mm/vmscan.c:352
Inline: False
Direct callers:
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/workingset.c:workingset_refault
```
**Symbols:**

```
c0000000003851d0-c000000000385310: lruvec_lru_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int lruvec_lru_size(struct lruvec *lruvec, enum lru_list lru, int zone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffe0001e83cc)
Location: mm/vmscan.c:352
Inline: False
Direct callers:
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/workingset.c:workingset_refault
```
**Symbols:**

```
ffffffe0001e83cc-ffffffe0001e84c0: lruvec_lru_size (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
long unsigned int lruvec_lru_size(struct lruvec *lruvec, enum lru_list lru, int zone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81230780)
Location: mm/vmscan.c:352
Inline: False
Direct callers:
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:inactive_list_is_low
  - mm/workingset.c:workingset_refault
```
**Symbols:**

```
ffffffff81230780-ffffffff8123087e: lruvec_lru_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int lruvec_lru_size(struct lruvec *lruvec, enum lru_list lru, int zone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81223840)
Location: mm/vmscan.c:352
Inline: False
Direct callers:
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:inactive_list_is_low
  - mm/workingset.c:workingset_refault
```
**Symbols:**

```
ffffffff81223840-ffffffff8122393e: lruvec_lru_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int lruvec_lru_size(struct lruvec *lruvec, enum lru_list lru, int zone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8122e520)
Location: mm/vmscan.c:352
Inline: False
Direct callers:
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:inactive_list_is_low
  - mm/workingset.c:workingset_refault
```
**Symbols:**

```
ffffffff8122e520-ffffffff8122e61e: lruvec_lru_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int lruvec_lru_size(struct lruvec *lruvec, enum lru_list lru, int zone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8123d910)
Location: mm/vmscan.c:352
Inline: False
Direct callers:
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:inactive_list_is_low
  - mm/workingset.c:workingset_refault
```
**Symbols:**

```
ffffffff8123d910-ffffffff8123da0e: lruvec_lru_size (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int zone_idx</code>
</li>
</ul>
</details>
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
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
