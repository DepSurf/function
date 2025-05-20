# Function: <code>part_stat_read_all</code>

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
void part_stat_read_all(struct hd_struct *part, struct disk_stats *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81559250)
Location: block/genhd.c:95
Inline: False
Direct callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_stat_show
```
**Symbols:**

```
ffffffff81559250-ffffffff815592e8: part_stat_read_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void part_stat_read_all(struct block_device *part, struct disk_stats *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81575a00)
Location: block/genhd.c:112
Inline: False
Direct callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_stat_show
```
**Symbols:**

```
ffffffff81575a00-ffffffff81575a98: part_stat_read_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void part_stat_read_all(struct block_device *part, struct disk_stats *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8157d830)
Location: block/genhd.c:109
Inline: False
Direct callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_stat_show
```
**Symbols:**

```
ffffffff8157d830-ffffffff8157d8c8: part_stat_read_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void part_stat_read_all(struct block_device *part, struct disk_stats *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff815e2a70)
Location: block/genhd.c:123
Inline: False
Direct callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_stat_show
```
**Symbols:**

```
ffffffff815e2a70-ffffffff815e2d07: part_stat_read_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void part_stat_read_all(struct block_device *part, struct disk_stats *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81691c00)
Location: block/genhd.c:127
Inline: False
Direct callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_stat_show
```
**Symbols:**

```
ffffffff81691c00-ffffffff81691ed7: part_stat_read_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void part_stat_read_all(struct block_device *part, struct disk_stats *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff817511a0)
Location: block/genhd.c:104
Inline: False
Direct callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_stat_show
```
**Symbols:**

```
ffffffff817511a0-ffffffff81751487: part_stat_read_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void part_stat_read_all(struct block_device *part, struct disk_stats *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8178d770)
Location: block/genhd.c:100
Inline: False
Direct callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_stat_show
```
**Symbols:**

```
ffffffff8178d770-ffffffff8178da08: part_stat_read_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void part_stat_read_all(struct block_device *part, struct disk_stats *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff817cffd0)
Location: block/genhd.c:100
Inline: False
Direct callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_stat_show
```
**Symbols:**

```
ffffffff817cffd0-ffffffff817d0268: part_stat_read_all (STB_LOCAL)
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
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct hd_struct *part</code> ➡️ <code>struct block_device *part</code>
</li>
</ul>
</details>
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
