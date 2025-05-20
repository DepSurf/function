# Function: <code>blk_mq_alloc_disk_for_queue</code>

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
struct gendisk *blk_mq_alloc_disk_for_queue(struct request_queue *q, struct lock_class_key *lkclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81740960)
Location: block/blk-mq.c:4123
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff81740960-ffffffff817409b8: blk_mq_alloc_disk_for_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct gendisk *blk_mq_alloc_disk_for_queue(struct request_queue *q, struct lock_class_key *lkclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8177cbd0)
Location: block/blk-mq.c:4135
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff8177cbd0-ffffffff8177cc3e: blk_mq_alloc_disk_for_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct gendisk *blk_mq_alloc_disk_for_queue(struct request_queue *q, struct lock_class_key *lkclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817befd0)
Location: block/blk-mq.c:4151
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff817befd0-ffffffff817bf03e: blk_mq_alloc_disk_for_queue (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
