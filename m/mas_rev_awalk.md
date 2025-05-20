# Function: <code>mas_rev_awalk</code>

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
bool mas_rev_awalk(struct ma_state *mas, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff8202ef70)
Location: lib/maple_tree.c:4884
Inline: False
Direct callers:
  - lib/maple_tree.c:mas_empty_area_rev
```
**Symbols:**

```
ffffffff8202ef70-ffffffff8202f2f1: mas_rev_awalk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool mas_rev_awalk(struct ma_state *mas, long unsigned int size, long unsigned int *gap_min, long unsigned int *gap_max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff820b1770)
Location: lib/maple_tree.c:4821
Inline: False
Direct callers:
  - lib/maple_tree.c:mas_empty_area_rev
```
**Symbols:**

```
ffffffff820b1770-ffffffff820b1af0: mas_rev_awalk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool mas_rev_awalk(struct ma_state *mas, long unsigned int size, long unsigned int *gap_min, long unsigned int *gap_max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff8217e980)
Location: lib/maple_tree.c:4694
Inline: False
Direct callers:
  - lib/maple_tree.c:mas_empty_area_rev
```
**Symbols:**

```
ffffffff8217e980-ffffffff8217ec4c: mas_rev_awalk (STB_LOCAL)
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
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int *gap_min</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int *gap_max</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
