# Function: <code>dm_stats_account_io</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dm_stats_account_io(struct dm_stats *stats, long unsigned int bi_rw, sector_t bi_sector, unsigned int bi_sectors, bool end, long unsigned int duration_jiffies, struct dm_stats_aux *stats_aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff816ad2e0)
Location: drivers/md/dm-stats.c:625
Inline: False
Direct callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dm_start_request
```
**Symbols:**

```
ffffffff816ad2e0-ffffffff816ad5f4: dm_stats_account_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dm_stats_account_io(struct dm_stats *stats, long unsigned int bi_rw, sector_t bi_sector, unsigned int bi_sectors, bool end, long unsigned int duration_jiffies, struct dm_stats_aux *stats_aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff8170d860)
Location: drivers/md/dm-stats.c:624
Inline: False
Direct callers:
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm-rq.c:dm_start_request
```
**Symbols:**

```
ffffffff8170d860-ffffffff8170db66: dm_stats_account_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dm_stats_account_io(struct dm_stats *stats, long unsigned int bi_rw, sector_t bi_sector, unsigned int bi_sectors, bool end, long unsigned int duration_jiffies, struct dm_stats_aux *stats_aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff8173fd20)
Location: drivers/md/dm-stats.c:625
Inline: False
Direct callers:
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm-rq.c:dm_start_request
```
**Symbols:**

```
ffffffff8173fd20-ffffffff81740026: dm_stats_account_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dm_stats_account_io(struct dm_stats *stats, long unsigned int bi_rw, sector_t bi_sector, unsigned int bi_sectors, bool end, long unsigned int duration_jiffies, struct dm_stats_aux *stats_aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff81759ac0)
Location: drivers/md/dm-stats.c:620
Inline: False
Direct callers:
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm-rq.c:dm_start_request
```
**Symbols:**

```
ffffffff81759ac0-ffffffff81759dbe: dm_stats_account_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dm_stats_account_io(struct dm_stats *stats, long unsigned int bi_rw, sector_t bi_sector, unsigned int bi_sectors, bool end, long unsigned int duration_jiffies, struct dm_stats_aux *stats_aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff817cbd00)
Location: drivers/md/dm-stats.c:621
Inline: False
Direct callers:
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm-rq.c:dm_start_request
```
**Symbols:**

```
ffffffff817cbd00-ffffffff817cbffd: dm_stats_account_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dm_stats_account_io(struct dm_stats *stats, long unsigned int bi_rw, sector_t bi_sector, unsigned int bi_sectors, bool end, long unsigned int duration_jiffies, struct dm_stats_aux *stats_aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff81814ae0)
Location: drivers/md/dm-stats.c:622
Inline: False
Direct callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:alloc_io
  - drivers/md/dm-rq.c:dm_start_request
```
**Symbols:**

```
ffffffff81814ae0-ffffffff81814dc9: dm_stats_account_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dm_stats_account_io(struct dm_stats *stats, long unsigned int bi_rw, sector_t bi_sector, unsigned int bi_sectors, bool end, long unsigned int duration_jiffies, struct dm_stats_aux *stats_aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff81840b00)
Location: drivers/md/dm-stats.c:622
Inline: False
Direct callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:alloc_io
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff81840b00-ffffffff81840dd3: dm_stats_account_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void dm_stats_account_io(struct dm_stats *stats, long unsigned int bi_rw, sector_t bi_sector, unsigned int bi_sectors, bool end, long unsigned int duration_jiffies, struct dm_stats_aux *stats_aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-stats.c (0)
Location: drivers/md/dm-stats.c:622
Inline: False
Direct callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:alloc_io
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff81884707-ffffffff81884721: dm_stats_account_io.cold (STB_LOCAL)
ffffffff81883d30-ffffffff81883fe2: dm_stats_account_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void dm_stats_account_io(struct dm_stats *stats, long unsigned int bi_rw, sector_t bi_sector, unsigned int bi_sectors, bool end, long unsigned int duration_jiffies, struct dm_stats_aux *stats_aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-stats.c (0)
Location: drivers/md/dm-stats.c:622
Inline: False
Direct callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:alloc_io
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff818b65fc-ffffffff818b6616: dm_stats_account_io.cold (STB_LOCAL)
ffffffff818b5c50-ffffffff818b5f02: dm_stats_account_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void dm_stats_account_io(struct dm_stats *stats, long unsigned int bi_rw, sector_t bi_sector, unsigned int bi_sectors, bool end, long unsigned int duration_jiffies, struct dm_stats_aux *stats_aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-stats.c (0)
Location: drivers/md/dm-stats.c:622
Inline: False
Direct callers:
  - drivers/md/dm.c:end_io_acct
  - drivers/md/dm.c:alloc_io
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_done
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff81986f2e-ffffffff81986f4e: dm_stats_account_io.cold (STB_LOCAL)
ffffffff81986980-ffffffff81986b30: dm_stats_account_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void dm_stats_account_io(struct dm_stats *stats, long unsigned int bi_rw, sector_t bi_sector, unsigned int bi_sectors, bool end, long unsigned int duration_jiffies, struct dm_stats_aux *stats_aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-stats.c (0)
Location: drivers/md/dm-stats.c:622
Inline: False
Direct callers:
  - drivers/md/dm.c:alloc_io
  - drivers/md/dm.c:end_io_acct
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_done
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff81c286b9-ffffffff81c286d9: dm_stats_account_io.cold (STB_LOCAL)
ffffffff8198a9c0-ffffffff8198ab75: dm_stats_account_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void dm_stats_account_io(struct dm_stats *stats, long unsigned int bi_rw, sector_t bi_sector, unsigned int bi_sectors, bool end, long unsigned int duration_jiffies, struct dm_stats_aux *stats_aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-stats.c (0)
Location: drivers/md/dm-stats.c:622
Inline: False
Direct callers:
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_done
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff81c1a898-ffffffff81c1a8b8: dm_stats_account_io.cold (STB_LOCAL)
ffffffff8196ef70-ffffffff8196f133: dm_stats_account_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dm_stats_account_io(struct dm_stats *stats, long unsigned int bi_rw, sector_t bi_sector, unsigned int bi_sectors, bool end, long unsigned int duration_jiffies, struct dm_stats_aux *stats_aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-stats.c (0)
Location: drivers/md/dm-stats.c:622
Inline: False
Direct callers:
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dm_io_dec_pending
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff81d2a794-ffffffff81d2a7b4: dm_stats_account_io.cold (STB_LOCAL)
ffffffff81a17890-ffffffff81a17a53: dm_stats_account_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dm_stats_account_io(struct dm_stats *stats, long unsigned int bi_rw, sector_t bi_sector, unsigned int bi_sectors, bool end, long unsigned int start_time, struct dm_stats_aux *stats_aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff81b80670)
Location: drivers/md/dm-stats.c:653
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_io_acct
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff81b80670-ffffffff81b80876: dm_stats_account_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dm_stats_account_io(struct dm_stats *stats, long unsigned int bi_rw, sector_t bi_sector, unsigned int bi_sectors, bool end, long unsigned int start_time, struct dm_stats_aux *stats_aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff81d1e920)
Location: drivers/md/dm-stats.c:653
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_io_acct
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff81d1e920-ffffffff81d1eb2d: dm_stats_account_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dm_stats_account_io(struct dm_stats *stats, long unsigned int bi_rw, sector_t bi_sector, unsigned int bi_sectors, bool end, long unsigned int start_time, struct dm_stats_aux *stats_aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff81d87b10)
Location: drivers/md/dm-stats.c:663
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_io_acct
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff81d87b10-ffffffff81d87d0c: dm_stats_account_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dm_stats_account_io(struct dm_stats *stats, long unsigned int bi_rw, sector_t bi_sector, unsigned int bi_sectors, bool end, long unsigned int start_time, struct dm_stats_aux *stats_aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff81e3f220)
Location: drivers/md/dm-stats.c:672
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_io_acct
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff81e3f220-ffffffff81e3f41c: dm_stats_account_io (STB_GLOBAL)
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
void dm_stats_account_io(struct dm_stats *stats, long unsigned int bi_rw, sector_t bi_sector, unsigned int bi_sectors, bool end, long unsigned int duration_jiffies, struct dm_stats_aux *stats_aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffff800010b0db90)
Location: drivers/md/dm-stats.c:622
Inline: False
Direct callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:alloc_io
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffff800010b0db90-ffff800010b0dec0: dm_stats_account_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dm_stats_account_io(struct dm_stats *stats, long unsigned int bi_rw, sector_t bi_sector, unsigned int bi_sectors, bool end, long unsigned int duration_jiffies, struct dm_stats_aux *stats_aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (c0bebd60)
Location: drivers/md/dm-stats.c:622
Inline: False
Direct callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:alloc_io
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
c0bebd60-c0bec288: dm_stats_account_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dm_stats_account_io(struct dm_stats *stats, long unsigned int bi_rw, sector_t bi_sector, unsigned int bi_sectors, bool end, long unsigned int duration_jiffies, struct dm_stats_aux *stats_aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (c000000000c00710)
Location: drivers/md/dm-stats.c:622
Inline: False
Direct callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:alloc_io
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
c000000000c00710-c000000000c00ae4: dm_stats_account_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dm_stats_account_io(struct dm_stats *stats, long unsigned int bi_rw, sector_t bi_sector, unsigned int bi_sectors, bool end, long unsigned int duration_jiffies, struct dm_stats_aux *stats_aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffe0006fad00)
Location: drivers/md/dm-stats.c:622
Inline: False
Direct callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:alloc_io
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffe0006fad00-ffffffe0006fafb4: dm_stats_account_io (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void dm_stats_account_io(struct dm_stats *stats, long unsigned int bi_rw, sector_t bi_sector, unsigned int bi_sectors, bool end, long unsigned int duration_jiffies, struct dm_stats_aux *stats_aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-stats.c (0)
Location: drivers/md/dm-stats.c:622
Inline: False
Direct callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:alloc_io
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff8185c47c-ffffffff8185c496: dm_stats_account_io.cold (STB_LOCAL)
ffffffff8185bad0-ffffffff8185bd82: dm_stats_account_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void dm_stats_account_io(struct dm_stats *stats, long unsigned int bi_rw, sector_t bi_sector, unsigned int bi_sectors, bool end, long unsigned int duration_jiffies, struct dm_stats_aux *stats_aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-stats.c (0)
Location: drivers/md/dm-stats.c:622
Inline: False
Direct callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:alloc_io
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff81823a4c-ffffffff81823a66: dm_stats_account_io.cold (STB_LOCAL)
ffffffff818230a0-ffffffff81823352: dm_stats_account_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void dm_stats_account_io(struct dm_stats *stats, long unsigned int bi_rw, sector_t bi_sector, unsigned int bi_sectors, bool end, long unsigned int duration_jiffies, struct dm_stats_aux *stats_aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-stats.c (0)
Location: drivers/md/dm-stats.c:622
Inline: False
Direct callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:alloc_io
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff818abaac-ffffffff818abac6: dm_stats_account_io.cold (STB_LOCAL)
ffffffff818ab100-ffffffff818ab3b2: dm_stats_account_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void dm_stats_account_io(struct dm_stats *stats, long unsigned int bi_rw, sector_t bi_sector, unsigned int bi_sectors, bool end, long unsigned int duration_jiffies, struct dm_stats_aux *stats_aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-stats.c (0)
Location: drivers/md/dm-stats.c:622
Inline: False
Direct callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:alloc_io
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff818c7cec-ffffffff818c7d06: dm_stats_account_io.cold (STB_LOCAL)
ffffffff818c7310-ffffffff818c75f4: dm_stats_account_io (STB_GLOBAL)
```
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int start_time</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int duration_jiffies</code>
</li>
</ul>
</details>
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
