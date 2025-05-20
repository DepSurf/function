# Function: <code>update_io_ticks</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void update_io_ticks(struct hd_struct *part, long unsigned int now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81499b20)
Location: block/bio.c:1664
Inline: False
Direct callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
```
**Symbols:**

```
ffffffff81499b20-ffffffff81499bad: update_io_ticks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void update_io_ticks(struct hd_struct *part, long unsigned int now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c7bd0)
Location: block/bio.c:1713
Inline: False
Direct callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
```
**Symbols:**

```
ffffffff814c7bd0-ffffffff814c7c35: update_io_ticks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void update_io_ticks(struct hd_struct *part, long unsigned int now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814e0cd0)
Location: block/bio.c:1755
Inline: False
Direct callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
```
**Symbols:**

```
ffffffff814e0cd0-ffffffff814e0d35: update_io_ticks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void update_io_ticks(struct hd_struct *part, long unsigned int now, bool end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815427f0)
Location: block/blk-core.c:1393
Inline: False
Direct callers:
  - block/blk-core.c:disk_end_io_acct
  - block/blk-core.c:disk_start_io_acct
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
```
**Symbols:**

```
ffffffff815427f0-ffffffff81542857: update_io_ticks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void update_io_ticks(struct block_device *part, long unsigned int now, bool end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8155eea0)
Location: block/blk-core.c:1265
Inline: False
Direct callers:
  - block/blk-core.c:__part_end_io_acct
  - block/blk-core.c:__part_start_io_acct
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
```
**Symbols:**

```
ffffffff8155eea0-ffffffff8155eefa: update_io_ticks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void update_io_ticks(struct block_device *part, long unsigned int now, bool end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815676f0)
Location: block/blk-core.c:1250
Inline: False
Direct callers:
  - block/blk-core.c:__part_end_io_acct
  - block/blk-core.c:__part_start_io_acct
  - block/blk-core.c:blk_account_io_done
```
**Symbols:**

```
ffffffff815676f0-ffffffff81567748: update_io_ticks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void update_io_ticks(struct block_device *part, long unsigned int now, bool end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815cbf90)
Location: block/blk-core.c:1227
Inline: False
Direct callers:
  - block/blk-core.c:__part_end_io_acct
  - block/blk-core.c:__part_start_io_acct
  - block/blk-core.c:blk_account_io_done
```
**Symbols:**

```
ffffffff815cbf90-ffffffff815cbfe8: update_io_ticks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void update_io_ticks(struct block_device *part, long unsigned int now, bool end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff816799c0)
Location: block/blk-core.c:984
Inline: False
Direct callers:
  - block/blk-core.c:bdev_end_io_acct
  - block/blk-core.c:bdev_start_io_acct
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_execute_rq
  - block/blk-mq.c:blk_execute_rq_nowait
  - block/blk-mq.c:__blk_account_io_done
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_stat_show
```
**Symbols:**

```
ffffffff816799c0-ffffffff81679a25: update_io_ticks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void update_io_ticks(struct block_device *part, long unsigned int now, bool end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81735e20)
Location: block/blk-core.c:934
Inline: False
Direct callers:
  - block/blk-core.c:bdev_end_io_acct
  - block/blk-core.c:bdev_start_io_acct
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_execute_rq
  - block/blk-mq.c:blk_execute_rq_nowait
  - block/blk-mq.c:__blk_account_io_done
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_stat_show
```
**Symbols:**

```
ffffffff81735e20-ffffffff81735e82: update_io_ticks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void update_io_ticks(struct block_device *part, long unsigned int now, bool end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81772410)
Location: block/blk-core.c:937
Inline: False
Direct callers:
  - block/blk-core.c:bdev_end_io_acct
  - block/blk-core.c:bio_start_io_acct
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_execute_rq
  - block/blk-mq.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_account_io_done
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_stat_show
```
**Symbols:**

```
ffffffff81772410-ffffffff8177246c: update_io_ticks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void update_io_ticks(struct block_device *part, long unsigned int now, bool end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff817b47b0)
Location: block/blk-core.c:972
Inline: False
Direct callers:
  - block/blk-core.c:bdev_end_io_acct
  - block/blk-core.c:bio_start_io_acct
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_execute_rq
  - block/blk-mq.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_account_io_done
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_stat_show
```
**Symbols:**

```
ffffffff817b47b0-ffffffff817b480c: update_io_ticks (STB_GLOBAL)
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
void update_io_ticks(struct hd_struct *part, long unsigned int now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffff8000105dd850)
Location: block/bio.c:1755
Inline: False
Direct callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
```
**Symbols:**

```
ffff8000105dd850-ffff8000105dd90c: update_io_ticks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void update_io_ticks(struct hd_struct *part, long unsigned int now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c078ac28)
Location: block/bio.c:1755
Inline: False
Direct callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
```
**Symbols:**

```
c078ac28-c078accc: update_io_ticks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void update_io_ticks(struct hd_struct *part, long unsigned int now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c00000000076f120)
Location: block/bio.c:1755
Inline: False
Direct callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
```
**Symbols:**

```
c00000000076f120-c00000000076f1c0: update_io_ticks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void update_io_ticks(struct hd_struct *part, long unsigned int now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffe0004208a8)
Location: block/bio.c:1755
Inline: False
Direct callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
```
**Symbols:**

```
ffffffe0004208a8-ffffffe00042092e: update_io_ticks (STB_GLOBAL)
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
void update_io_ticks(struct hd_struct *part, long unsigned int now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d92b0)
Location: block/bio.c:1755
Inline: False
Direct callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
```
**Symbols:**

```
ffffffff814d92b0-ffffffff814d9315: update_io_ticks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void update_io_ticks(struct hd_struct *part, long unsigned int now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c9c60)
Location: block/bio.c:1755
Inline: False
Direct callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
```
**Symbols:**

```
ffffffff814c9c60-ffffffff814c9cc5: update_io_ticks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void update_io_ticks(struct hd_struct *part, long unsigned int now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d5340)
Location: block/bio.c:1755
Inline: False
Direct callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
```
**Symbols:**

```
ffffffff814d5340-ffffffff814d53a5: update_io_ticks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void update_io_ticks(struct hd_struct *part, long unsigned int now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814edef0)
Location: block/bio.c:1755
Inline: False
Direct callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
```
**Symbols:**

```
ffffffff814edef0-ffffffff814edf55: update_io_ticks (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool end</code>
</li>
</ul>
</details>
</li>
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
