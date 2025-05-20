# Function: <code>part_round_stats</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void part_round_stats(int cpu, struct hd_struct *part);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813b54a0)
Location: block/blk-core.c:1440
Inline: False
Direct callers:
  - block/bio.c:generic_start_io_acct
  - block/bio.c:generic_end_io_acct
  - block/blk-core.c:blk_account_io_start
  - block/blk-merge.c:attempt_merge
  - block/genhd.c:diskstats_show
  - block/partition-generic.c:part_stat_show
  - drivers/nvdimm/core.c:__nd_iostat_start
  - drivers/nvdimm/core.c:nd_iostat_end
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff813b54a0-ffffffff813b54fa: part_round_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void part_round_stats(int cpu, struct hd_struct *part);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fa320)
Location: block/blk-core.c:1399
Inline: False
Direct callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
  - block/blk-core.c:blk_account_io_start
  - block/genhd.c:diskstats_show
  - block/partition-generic.c:part_stat_show
  - drivers/nvdimm/core.c:nd_iostat_end
  - drivers/nvdimm/core.c:__nd_iostat_start
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff813fa320-ffffffff813fa37a: part_round_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void part_round_stats(int cpu, struct hd_struct *part);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81413ca0)
Location: block/blk-core.c:1401
Inline: False
Direct callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
  - block/blk-core.c:blk_account_io_start
  - block/genhd.c:diskstats_show
  - block/partition-generic.c:part_stat_show
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff81413ca0-ffffffff81413cfa: part_round_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void part_round_stats(int cpu, struct hd_struct *part);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81421780)
Location: block/blk-core.c:1505
Inline: False
Direct callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
  - block/blk-core.c:blk_account_io_start
  - block/blk-merge.c:attempt_merge
  - block/genhd.c:diskstats_show
  - block/partition-generic.c:part_stat_show
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff81421780-ffffffff814217da: part_round_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void part_round_stats(struct request_queue *q, int cpu, struct hd_struct *part);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8144c9d0)
Location: block/blk-core.c:1606
Inline: False
Direct callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
  - block/blk-core.c:blk_account_io_start
  - block/blk-merge.c:attempt_merge
  - block/genhd.c:diskstats_show
  - block/partition-generic.c:part_stat_show
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff8144c9d0-ffffffff8144cb40: part_round_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void part_round_stats(struct request_queue *q, int cpu, struct hd_struct *part);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8147fce0)
Location: block/blk-core.c:1702
Inline: False
Direct callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
  - block/blk-core.c:blk_account_io_start
  - block/genhd.c:diskstats_show
  - block/partition-generic.c:part_stat_show
```
**Symbols:**

```
ffffffff8147fce0-ffffffff8147fe53: part_round_stats (STB_GLOBAL)
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
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct request_queue *q</code>
</li>
<li>
<b>Param reordered. </b>
<code>cpu, part</code> ➡️ <code>q, cpu, part</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
