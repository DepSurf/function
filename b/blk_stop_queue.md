# Function: <code>blk_stop_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_stop_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813b55e0)
Location: block/blk-core.c:257
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block
  - drivers/md/dm.c:old_stop_queue
```
**Symbols:**

```
ffffffff813b55e0-ffffffff813b5604: blk_stop_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_stop_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fa460)
Location: block/blk-core.c:257
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block
  - drivers/md/dm-rq.c:dm_stop_queue
```
**Symbols:**

```
ffffffff813fa460-ffffffff813fa484: blk_stop_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_stop_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81413de0)
Location: block/blk-core.c:258
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block
  - drivers/md/dm-rq.c:dm_stop_queue
```
**Symbols:**

```
ffffffff81413de0-ffffffff81413e04: blk_stop_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_stop_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81421890)
Location: block/blk-core.c:305
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait
  - drivers/md/dm-rq.c:dm_stop_queue
```
**Symbols:**

```
ffffffff81421890-ffffffff814218c2: blk_stop_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_stop_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8144c370)
Location: block/blk-core.c:305
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait
  - drivers/md/dm-rq.c:dm_stop_queue
```
**Symbols:**

```
ffffffff8144c370-ffffffff8144c3a2: blk_stop_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_stop_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8147f620)
Location: block/blk-core.c:377
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait
  - drivers/md/dm-rq.c:dm_stop_queue
```
**Symbols:**

```
ffffffff8147f620-ffffffff8147f653: blk_stop_queue (STB_GLOBAL)
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
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
