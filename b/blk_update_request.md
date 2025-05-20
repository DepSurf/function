# Function: <code>blk_update_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool blk_update_request(struct request *req, int error, unsigned int nr_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813ba1a0)
Location: block/blk-core.c:2567
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/md/dm.c:end_clone_bio
```
**Symbols:**

```
ffffffff813ba1a0-ffffffff813ba4ab: blk_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool blk_update_request(struct request *req, int error, unsigned int nr_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fdf60)
Location: block/blk-core.c:2539
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/md/dm-rq.c:end_clone_bio
```
**Symbols:**

```
ffffffff813fdf60-ffffffff813fe257: blk_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool blk_update_request(struct request *req, int error, unsigned int nr_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814178a0)
Location: block/blk-core.c:2528
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/md/dm-rq.c:end_clone_bio
```
**Symbols:**

```
ffffffff814178a0-ffffffff81417bf4: blk_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool blk_update_request(struct request *req, blk_status_t error, unsigned int nr_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814256e0)
Location: block/blk-core.c:2708
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/md/dm-rq.c:end_clone_bio
```
**Symbols:**

```
ffffffff814256e0-ffffffff814259ad: blk_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool blk_update_request(struct request *req, blk_status_t error, unsigned int nr_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81450880)
Location: block/blk-core.c:2932
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/md/dm-rq.c:end_clone_bio
```
**Symbols:**

```
ffffffff81450880-ffffffff81450b38: blk_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
bool blk_update_request(struct request *req, blk_status_t error, unsigned int nr_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-core.c (0)
Location: block/blk-core.c:3076
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_complete_rq
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/md/dm-rq.c:end_clone_bio
```
**Symbols:**

```
ffffffff81485769-ffffffff814857d7: blk_update_request.cold.101 (STB_LOCAL)
ffffffff81483b90-ffffffff81483de9: blk_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
bool blk_update_request(struct request *req, blk_status_t error, unsigned int nr_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-core.c (0)
Location: block/blk-core.c:1432
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_complete_rq
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/md/dm-rq.c:end_clone_bio
```
**Symbols:**

```
ffffffff8149ffdc-ffffffff814a004e: blk_update_request.cold.65 (STB_LOCAL)
ffffffff8149f150-ffffffff8149f3a9: blk_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
bool blk_update_request(struct request *req, blk_status_t error, unsigned int nr_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-core.c (0)
Location: block/blk-core.c:1398
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_complete_rq
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/md/dm-rq.c:end_clone_bio
```
**Symbols:**

```
ffffffff814ce02a-ffffffff814ce0e6: blk_update_request.cold (STB_LOCAL)
ffffffff814cd230-ffffffff814cd4a6: blk_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
bool blk_update_request(struct request *req, blk_status_t error, unsigned int nr_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-core.c (0)
Location: block/blk-core.c:1433
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_complete_rq
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/md/dm-rq.c:end_clone_bio
```
**Symbols:**

```
ffffffff814e734a-ffffffff814e740a: blk_update_request.cold (STB_LOCAL)
ffffffff814e64c0-ffffffff814e6795: blk_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
bool blk_update_request(struct request *req, blk_status_t error, unsigned int nr_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-core.c (0)
Location: block/blk-core.c:1538
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - drivers/block/loop.c:lo_complete_rq
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/md/dm-rq.c:end_clone_bio
```
**Symbols:**

```
ffffffff8154632e-ffffffff81546358: blk_update_request.cold (STB_LOCAL)
ffffffff81543750-ffffffff81543add: blk_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
bool blk_update_request(struct request *req, blk_status_t error, unsigned int nr_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-core.c (0)
Location: block/blk-core.c:1430
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - drivers/block/loop.c:lo_complete_rq
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/md/dm-rq.c:end_clone_bio
```
**Symbols:**

```
ffffffff81bf2685-ffffffff81bf26af: blk_update_request.cold (STB_LOCAL)
ffffffff81560630-ffffffff8156099e: blk_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool blk_update_request(struct request *req, blk_status_t error, unsigned int nr_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-core.c (0)
Location: block/blk-core.c:1422
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - drivers/block/loop.c:lo_complete_rq
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/md/dm-rq.c:end_clone_bio
```
**Symbols:**

```
ffffffff81be45b7-ffffffff81be4676: blk_update_request.cold (STB_LOCAL)
ffffffff81568c90-ffffffff81569025: blk_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool blk_update_request(struct request *req, blk_status_t error, unsigned int nr_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-core.c (0)
Location: block/blk-core.c:1408
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - drivers/block/loop.c:lo_complete_rq
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/md/dm-rq.c:end_clone_bio
```
**Symbols:**

```
ffffffff81cd809f-ffffffff81cd80c9: blk_update_request.cold (STB_LOCAL)
ffffffff815ccf20-ffffffff815cd3f0: blk_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool blk_update_request(struct request *req, blk_status_t error, unsigned int nr_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:783
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - drivers/block/loop.c:lo_complete_rq
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/md/dm-rq.c:end_clone_bio
```
**Symbols:**

```
ffffffff81e8bac7-ffffffff81e8baea: blk_update_request.cold (STB_LOCAL)
ffffffff81686dc0-ffffffff81687218: blk_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool blk_update_request(struct request *req, blk_status_t error, unsigned int nr_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81744aa0)
Location: block/blk-mq.c:892
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - drivers/block/loop.c:lo_complete_rq
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/md/dm-rq.c:end_clone_bio
```
**Symbols:**

```
ffffffff81744aa0-ffffffff81744f6f: blk_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool blk_update_request(struct request *req, blk_status_t error, unsigned int nr_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817808c0)
Location: block/blk-mq.c:885
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_end_request
  - drivers/block/loop.c:lo_complete_rq
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/md/dm-rq.c:end_clone_bio
```
**Symbols:**

```
ffffffff817808c0-ffffffff81780df5: blk_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool blk_update_request(struct request *req, blk_status_t error, unsigned int nr_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c2e80)
Location: block/blk-mq.c:895
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_end_request
  - drivers/block/loop.c:lo_complete_rq
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/md/dm-rq.c:end_clone_bio
```
**Symbols:**

```
ffffffff817c2e80-ffffffff817c33b3: blk_update_request (STB_GLOBAL)
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
bool blk_update_request(struct request *req, blk_status_t error, unsigned int nr_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffff8000105e3b88)
Location: block/blk-core.c:1433
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_complete_rq
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/md/dm-rq.c:end_clone_bio
  - drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery
  - drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery
  - drivers/mmc/core/block.c:mmc_blk_cqe_complete_rq
```
**Symbols:**

```
ffff8000105e3b88-ffff8000105e3f50: blk_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool blk_update_request(struct request *req, blk_status_t error, unsigned int nr_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c0790e40)
Location: block/blk-core.c:1433
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_complete_rq
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/mtd/mtd_blkdevs.c:mtd_blktrans_work
  - drivers/md/dm-rq.c:end_clone_bio
  - drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery
  - drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery
  - drivers/mmc/core/block.c:mmc_blk_cqe_complete_rq
```
**Symbols:**

```
c0790e40-c079122c: blk_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool blk_update_request(struct request *req, blk_status_t error, unsigned int nr_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c0000000007776b0)
Location: block/blk-core.c:1433
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_complete_rq
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/md/dm-rq.c:end_clone_bio
```
**Symbols:**

```
c0000000007776b0-c000000000777c08: blk_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool blk_update_request(struct request *req, blk_status_t error, unsigned int nr_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffe000425574)
Location: block/blk-core.c:1433
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_complete_rq
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/md/dm-rq.c:end_clone_bio
  - drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery
  - drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery
  - drivers/mmc/core/block.c:mmc_blk_cqe_complete_rq
```
**Symbols:**

```
ffffffe000425574-ffffffe0004258c4: blk_update_request (STB_GLOBAL)
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
bool blk_update_request(struct request *req, blk_status_t error, unsigned int nr_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-core.c (0)
Location: block/blk-core.c:1433
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_complete_rq
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/md/dm-rq.c:end_clone_bio
```
**Symbols:**

```
ffffffff814df92a-ffffffff814df9ea: blk_update_request.cold (STB_LOCAL)
ffffffff814deaa0-ffffffff814ded75: blk_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
bool blk_update_request(struct request *req, blk_status_t error, unsigned int nr_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-core.c (0)
Location: block/blk-core.c:1433
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_complete_rq
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/md/dm-rq.c:end_clone_bio
```
**Symbols:**

```
ffffffff814d02ca-ffffffff814d038a: blk_update_request.cold (STB_LOCAL)
ffffffff814cf440-ffffffff814cf715: blk_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
bool blk_update_request(struct request *req, blk_status_t error, unsigned int nr_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-core.c (0)
Location: block/blk-core.c:1433
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_complete_rq
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/md/dm-rq.c:end_clone_bio
```
**Symbols:**

```
ffffffff814db9ba-ffffffff814dba7a: blk_update_request.cold (STB_LOCAL)
ffffffff814dab30-ffffffff814dae05: blk_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
bool blk_update_request(struct request *req, blk_status_t error, unsigned int nr_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-core.c (0)
Location: block/blk-core.c:1433
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_complete_rq
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/md/dm-rq.c:end_clone_bio
```
**Symbols:**

```
ffffffff814f482f-ffffffff814f48ef: blk_update_request.cold (STB_LOCAL)
ffffffff814f38b0-ffffffff814f3b95: blk_update_request (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int error</code> ➡️ <code>blk_status_t error</code>
</li>
</ul>
</details>
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
