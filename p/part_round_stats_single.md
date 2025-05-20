# Function: <code>part_round_stats_single</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void part_round_stats_single(int cpu, struct hd_struct *part, long unsigned int now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813b45c0)
Location: block/blk-core.c:1407
Inline: False
Direct callers:
  - block/blk-core.c:part_round_stats
  - block/blk-core.c:part_round_stats
```
**Symbols:**

```
ffffffff813b45c0-ffffffff813b462d: part_round_stats_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void part_round_stats_single(int cpu, struct hd_struct *part, long unsigned int now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813f82b0)
Location: block/blk-core.c:1366
Inline: False
Direct callers:
  - block/blk-core.c:part_round_stats
  - block/blk-core.c:part_round_stats
```
**Symbols:**

```
ffffffff813f82b0-ffffffff813f831d: part_round_stats_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void part_round_stats_single(int cpu, struct hd_struct *part, long unsigned int now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81411cd0)
Location: block/blk-core.c:1368
Inline: False
Direct callers:
  - block/blk-core.c:part_round_stats
  - block/blk-core.c:part_round_stats
```
**Symbols:**

```
ffffffff81411cd0-ffffffff81411d3d: part_round_stats_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void part_round_stats_single(int cpu, struct hd_struct *part, long unsigned int now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8141fb10)
Location: block/blk-core.c:1472
Inline: False
Direct callers:
  - block/blk-core.c:part_round_stats
  - block/blk-core.c:part_round_stats
```
**Symbols:**

```
ffffffff8141fb10-ffffffff8141fb7d: part_round_stats_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8144ca32)
Location: block/blk-core.c:1577
Inline: True
Inline callers:
  - block/blk-core.c:part_round_stats
  - block/blk-core.c:part_round_stats
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8147fd58)
Location: block/blk-core.c:1673
Inline: True
Inline callers:
  - block/blk-core.c:part_round_stats
  - block/blk-core.c:part_round_stats
```
</details>
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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
</ul>
