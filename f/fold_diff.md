# Function: <code>fold_diff</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811ad30c)
Location: mm/vmstat.c:434
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:cpu_vm_stats_fold
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fold_diff(int *zone_diff, int *node_diff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811c5380)
Location: mm/vmstat.c:607
Inline: False
Direct callers:
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
```
**Symbols:**

```
ffffffff811c5380-ffffffff811c53df: fold_diff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fold_diff(int *zone_diff, int *node_diff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811d5490)
Location: mm/vmstat.c:607
Inline: False
Direct callers:
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
```
**Symbols:**

```
ffffffff811d5490-ffffffff811d54ef: fold_diff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fold_diff(int *zone_diff, int *node_diff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811de310)
Location: mm/vmstat.c:607
Inline: False
Direct callers:
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
```
**Symbols:**

```
ffffffff811de310-ffffffff811de35d: fold_diff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fold_diff(int *zone_diff, int *numa_diff, int *node_diff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811f3da0)
Location: mm/vmstat.c:683
Inline: False
Direct callers:
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
```
**Symbols:**

```
ffffffff811f3da0-ffffffff811f3e1d: fold_diff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fold_diff(int *zone_diff, int *numa_diff, int *node_diff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81215190)
Location: mm/vmstat.c:683
Inline: False
Direct callers:
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
```
**Symbols:**

```
ffffffff81215190-ffffffff81215212: fold_diff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fold_diff(int *zone_diff, int *numa_diff, int *node_diff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81228070)
Location: mm/vmstat.c:683
Inline: False
Direct callers:
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
```
**Symbols:**

```
ffffffff81228070-ffffffff812280f1: fold_diff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fold_diff(int *zone_diff, int *numa_diff, int *node_diff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81237ce0)
Location: mm/vmstat.c:684
Inline: False
Direct callers:
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
```
**Symbols:**

```
ffffffff81237ce0-ffffffff81237d54: fold_diff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fold_diff(int *zone_diff, int *numa_diff, int *node_diff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81245f90)
Location: mm/vmstat.c:684
Inline: False
Direct callers:
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
```
**Symbols:**

```
ffffffff81245f90-ffffffff81246004: fold_diff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fold_diff(int *zone_diff, int *numa_diff, int *node_diff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81273c10)
Location: mm/vmstat.c:684
Inline: False
Direct callers:
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
```
**Symbols:**

```
ffffffff81273c10-ffffffff81273c9a: fold_diff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fold_diff(int *zone_diff, int *numa_diff, int *node_diff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8127e490)
Location: mm/vmstat.c:698
Inline: False
Direct callers:
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
```
**Symbols:**

```
ffffffff8127e490-ffffffff8127e51a: fold_diff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fold_diff(int *zone_diff, int *numa_diff, int *node_diff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812835f0)
Location: mm/vmstat.c:710
Inline: False
Direct callers:
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
```
**Symbols:**

```
ffffffff812835f0-ffffffff81283673: fold_diff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fold_diff(int *zone_diff, int *node_diff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812c1810)
Location: mm/vmstat.c:755
Inline: False
Direct callers:
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
```
**Symbols:**

```
ffffffff812c1810-ffffffff812c18c7: fold_diff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fold_diff(int *zone_diff, int *node_diff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8131e910)
Location: mm/vmstat.c:784
Inline: False
Direct callers:
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
```
**Symbols:**

```
ffffffff8131e910-ffffffff8131e9d2: fold_diff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fold_diff(int *zone_diff, int *node_diff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81392440)
Location: mm/vmstat.c:771
Inline: False
Direct callers:
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
```
**Symbols:**

```
ffffffff81392440-ffffffff81392502: fold_diff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fold_diff(int *zone_diff, int *node_diff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813c4e40)
Location: mm/vmstat.c:772
Inline: False
Direct callers:
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
```
**Symbols:**

```
ffffffff813c4e40-ffffffff813c4f02: fold_diff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fold_diff(int *zone_diff, int *node_diff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813ef860)
Location: mm/vmstat.c:773
Inline: False
Direct callers:
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
```
**Symbols:**

```
ffffffff813ef860-ffffffff813ef922: fold_diff (STB_LOCAL)
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
int fold_diff(int *zone_diff, int *numa_diff, int *node_diff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffff8000102daab8)
Location: mm/vmstat.c:684
Inline: False
Direct callers:
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
```
**Symbols:**

```
ffff8000102daab8-ffff8000102dabf8: fold_diff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fold_diff(int *zone_diff, int *node_diff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (c0500648)
Location: mm/vmstat.c:709
Inline: False
Direct callers:
  - mm/vmstat.c:cpu_vm_stats_fold
```
**Symbols:**

```
c0500648-c05006ec: fold_diff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fold_diff(int *zone_diff, int *numa_diff, int *node_diff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (c000000000399250)
Location: mm/vmstat.c:684
Inline: False
Direct callers:
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
```
**Symbols:**

```
c000000000399250-c000000000399338: fold_diff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fold_diff(int *zone_diff, int *node_diff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffe0001f3830)
Location: mm/vmstat.c:709
Inline: False
Direct callers:
  - mm/vmstat.c:cpu_vm_stats_fold
```
**Symbols:**

```
ffffffe0001f3830-ffffffe0001f38a0: fold_diff (STB_LOCAL)
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
int fold_diff(int *zone_diff, int *numa_diff, int *node_diff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8123e5e0)
Location: mm/vmstat.c:684
Inline: False
Direct callers:
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
```
**Symbols:**

```
ffffffff8123e5e0-ffffffff8123e654: fold_diff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fold_diff(int *zone_diff, int *numa_diff, int *node_diff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812315e0)
Location: mm/vmstat.c:684
Inline: False
Direct callers:
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
```
**Symbols:**

```
ffffffff812315e0-ffffffff81231654: fold_diff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fold_diff(int *zone_diff, int *numa_diff, int *node_diff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8123c380)
Location: mm/vmstat.c:684
Inline: False
Direct callers:
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
```
**Symbols:**

```
ffffffff8123c380-ffffffff8123c3f4: fold_diff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fold_diff(int *zone_diff, int *numa_diff, int *node_diff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8124bae0)
Location: mm/vmstat.c:684
Inline: False
Direct callers:
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
```
**Symbols:**

```
ffffffff8124bae0-ffffffff8124bb54: fold_diff (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int *numa_diff</code>
</li>
<li>
<b>Param reordered. </b>
<code>zone_diff, node_diff</code> ➡️ <code>zone_diff, numa_diff, node_diff</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int *numa_diff</code>
</li>
<li>
<b>Param reordered. </b>
<code>zone_diff, numa_diff, node_diff</code> ➡️ <code>zone_diff, node_diff</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>amd64</code> and <code>armhf</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int *numa_diff</code>
</li>
<li>
<b>Param reordered. </b>
<code>zone_diff, numa_diff, node_diff</code> ➡️ <code>zone_diff, node_diff</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>riscv64</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int *numa_diff</code>
</li>
<li>
<b>Param reordered. </b>
<code>zone_diff, numa_diff, node_diff</code> ➡️ <code>zone_diff, node_diff</code>
</li>
</ul>
</details>
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
