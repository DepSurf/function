# Function: <code>blk_complete_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_complete_request(struct request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-softirq.c (ffffffff813c1f50)
Location: block/blk-softirq.c:166
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_job_done
  - drivers/scsi/scsi_lib.c:scsi_done
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/md/dm.c:end_clone_request
  - drivers/md/dm.c:end_clone_request
  - drivers/md/dm.c:map_request
  - drivers/md/dm.c:map_request
  - drivers/md/dm.c:dm_request_fn
```
**Symbols:**

```
ffffffff813c1f50-ffffffff813c1f69: blk_complete_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_complete_request(struct request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-softirq.c (ffffffff81405ee0)
Location: block/blk-softirq.c:166
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_job_done
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_done
  - drivers/md/dm-rq.c:dm_complete_request
```
**Symbols:**

```
ffffffff81405ee0-ffffffff81405ef9: blk_complete_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_complete_request(struct request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-softirq.c (ffffffff81420170)
Location: block/blk-softirq.c:157
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_job_done
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_done
  - drivers/md/dm-rq.c:dm_complete_request
```
**Symbols:**

```
ffffffff81420170-ffffffff81420189: blk_complete_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_complete_request(struct request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-softirq.c (ffffffff8142e130)
Location: block/blk-softirq.c:158
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_job_done
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_done
  - drivers/md/dm-rq.c:dm_complete_request
```
**Symbols:**

```
ffffffff8142e130-ffffffff8142e14a: blk_complete_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_complete_request(struct request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-softirq.c (ffffffff81459360)
Location: block/blk-softirq.c:159
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_job_done
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_done
  - drivers/md/dm-rq.c:dm_complete_request
```
**Symbols:**

```
ffffffff81459360-ffffffff8145937a: blk_complete_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_complete_request(struct request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-softirq.c (ffffffff8148c8b0)
Location: block/blk-softirq.c:160
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_job_done
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_done
  - drivers/md/dm-rq.c:dm_complete_request
```
**Symbols:**

```
ffffffff8148c8b0-ffffffff8148c8ce: blk_complete_request (STB_GLOBAL)
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
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8168628b)
Location: block/blk-mq.c:720
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_end_request_batch
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
In block/blk-mq.c (ffffffff817443db)
Location: block/blk-mq.c:827
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_end_request_batch
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
In block/blk-mq.c (ffffffff8177fdfb)
Location: block/blk-mq.c:814
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_end_request_batch
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
In block/blk-mq.c (ffffffff817c163b)
Location: block/blk-mq.c:824
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_end_request_batch
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
</ul>
