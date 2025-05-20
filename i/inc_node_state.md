# Function: <code>inc_node_state</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void inc_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811c6e70)
Location: mm/vmstat.c:506
Inline: False
Direct callers:
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
```
**Symbols:**

```
ffffffff811c6e70-ffffffff811c6eec: inc_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void inc_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811d6f90)
Location: mm/vmstat.c:506
Inline: False
Direct callers:
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
```
**Symbols:**

```
ffffffff811d6f90-ffffffff811d700c: inc_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void inc_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811dfdf0)
Location: mm/vmstat.c:506
Inline: False
```
**Symbols:**

```
ffffffff811dfdf0-ffffffff811dfe68: inc_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void inc_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811f5c00)
Location: mm/vmstat.c:581
Inline: False
```
**Symbols:**

```
ffffffff811f5c00-ffffffff811f5c78: inc_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void inc_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81216e80)
Location: mm/vmstat.c:581
Inline: False
```
**Symbols:**

```
ffffffff81216e80-ffffffff81216ef8: inc_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void inc_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81229d90)
Location: mm/vmstat.c:581
Inline: False
```
**Symbols:**

```
ffffffff81229d90-ffffffff81229e08: inc_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void inc_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81239a20)
Location: mm/vmstat.c:582
Inline: False
```
**Symbols:**

```
ffffffff81239a20-ffffffff81239a98: inc_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void inc_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81247d20)
Location: mm/vmstat.c:582
Inline: False
```
**Symbols:**

```
ffffffff81247d20-ffffffff81247d98: inc_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void inc_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81275e50)
Location: mm/vmstat.c:582
Inline: False
```
**Symbols:**

```
ffffffff81275e50-ffffffff81275ecc: inc_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void inc_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81280730)
Location: mm/vmstat.c:596
Inline: False
```
**Symbols:**

```
ffffffff81280730-ffffffff812807c6: inc_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void inc_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81285850)
Location: mm/vmstat.c:608
Inline: False
```
**Symbols:**

```
ffffffff81285850-ffffffff812858df: inc_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void inc_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812c43a0)
Location: mm/vmstat.c:654
Inline: False
```
**Symbols:**

```
ffffffff812c43a0-ffffffff812c444a: inc_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void inc_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81321c50)
Location: mm/vmstat.c:683
Inline: False
```
**Symbols:**

```
ffffffff81321c50-ffffffff81321d2e: inc_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void inc_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81395d10)
Location: mm/vmstat.c:670
Inline: False
```
**Symbols:**

```
ffffffff81395d10-ffffffff81395e04: inc_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void inc_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813c8940)
Location: mm/vmstat.c:671
Inline: False
```
**Symbols:**

```
ffffffff813c8940-ffffffff813c8a34: inc_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void inc_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813f3330)
Location: mm/vmstat.c:672
Inline: False
```
**Symbols:**

```
ffffffff813f3330-ffffffff813f341f: inc_node_state (STB_GLOBAL)
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
void inc_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffff8000102dc4b8)
Location: mm/vmstat.c:582
Inline: False
```
**Symbols:**

```
ffff8000102dc4b8-ffff8000102dc5e8: inc_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void inc_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (c05021c0)
Location: mm/vmstat.c:635
Inline: False
```
**Symbols:**

```
c05021c0-c05021e8: inc_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void inc_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (c00000000039be70)
Location: mm/vmstat.c:635
Inline: False
```
**Symbols:**

```
c00000000039be70-c00000000039bec0: inc_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void inc_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffe0001f52fa)
Location: mm/vmstat.c:635
Inline: False
```
**Symbols:**

```
ffffffe0001f52fa-ffffffe0001f533a: inc_node_state (STB_GLOBAL)
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
void inc_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81240370)
Location: mm/vmstat.c:582
Inline: False
```
**Symbols:**

```
ffffffff81240370-ffffffff812403e8: inc_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void inc_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81233370)
Location: mm/vmstat.c:582
Inline: False
```
**Symbols:**

```
ffffffff81233370-ffffffff812333e8: inc_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void inc_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8123e110)
Location: mm/vmstat.c:582
Inline: False
```
**Symbols:**

```
ffffffff8123e110-ffffffff8123e188: inc_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void inc_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8124d840)
Location: mm/vmstat.c:582
Inline: False
```
**Symbols:**

```
ffffffff8124d840-ffffffff8124d8b8: inc_node_state (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
