# Function: <code>blk_mq_quiesce_queue_nowait</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_mq_quiesce_queue_nowait(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8142ec30)
Location: block/blk-mq.c:157
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_quiesce_queue
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait
```
**Symbols:**

```
ffffffff8142ec30-ffffffff8142ec63: blk_mq_quiesce_queue_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_mq_quiesce_queue_nowait(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145a0c0)
Location: block/blk-mq.c:196
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_quiesce_queue
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait
```
**Symbols:**

```
ffffffff8145a0c0-ffffffff8145a0f3: blk_mq_quiesce_queue_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_quiesce_queue_nowait(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8148db05)
Location: block/blk-mq.c:211
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_quiesce_queue
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait
```
**Symbols:**

```
ffffffff8148dae0-ffffffff8148daf8: blk_mq_quiesce_queue_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_quiesce_queue_nowait(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814a7395)
Location: block/blk-mq.c:215
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_quiesce_queue
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait
```
**Symbols:**

```
ffffffff814a7370-ffffffff814a7388: blk_mq_quiesce_queue_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_quiesce_queue_nowait(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d5335)
Location: block/blk-mq.c:218
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_quiesce_queue
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait
```
**Symbols:**

```
ffffffff814d5310-ffffffff814d5328: blk_mq_quiesce_queue_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_quiesce_queue_nowait(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814ee615)
Location: block/blk-mq.c:219
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_quiesce_queue
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait
```
**Symbols:**

```
ffffffff814ee5f0-ffffffff814ee608: blk_mq_quiesce_queue_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_quiesce_queue_nowait(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8154e285)
Location: block/blk-mq.c:204
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_quiesce_queue
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:device_block
```
**Symbols:**

```
ffffffff8154e260-ffffffff8154e278: blk_mq_quiesce_queue_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_quiesce_queue_nowait(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156a715)
Location: block/blk-mq.c:208
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_quiesce_queue
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:device_block
```
**Symbols:**

```
ffffffff8156a6f0-ffffffff8156a708: blk_mq_quiesce_queue_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_quiesce_queue_nowait(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81572655)
Location: block/blk-mq.c:208
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_quiesce_queue
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:device_block
```
**Symbols:**

```
ffffffff81572630-ffffffff81572648: blk_mq_quiesce_queue_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_quiesce_queue_nowait(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815d6c85)
Location: block/blk-mq.c:215
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_quiesce_queue
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:device_block
```
**Symbols:**

```
ffffffff815d6c60-ffffffff815d6c78: blk_mq_quiesce_queue_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_quiesce_queue_nowait(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8168bb5c)
Location: block/blk-mq.c:244
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_host_block
```
**Symbols:**

```
ffffffff81682920-ffffffff81682980: blk_mq_quiesce_queue_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_quiesce_queue_nowait(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8174a23c)
Location: block/blk-mq.c:244
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_quiesce_tagset
```
**Symbols:**

```
ffffffff81740050-ffffffff817400b0: blk_mq_quiesce_queue_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_quiesce_queue_nowait(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8178693f)
Location: block/blk-mq.c:203
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_quiesce_tagset
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:scsi_device_block
```
**Symbols:**

```
ffffffff8177c530-ffffffff8177c593: blk_mq_quiesce_queue_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_quiesce_queue_nowait(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c901c)
Location: block/blk-mq.c:203
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_quiesce_tagset
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:scsi_device_block
```
**Symbols:**

```
ffffffff817be8d0-ffffffff817be92a: blk_mq_quiesce_queue_nowait (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_quiesce_queue_nowait(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105ed2cc)
Location: block/blk-mq.c:219
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_quiesce_queue
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait
```
**Symbols:**

```
ffff8000105ed280-ffff8000105ed2b0: blk_mq_quiesce_queue_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_quiesce_queue_nowait(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c07997d4)
Location: block/blk-mq.c:219
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_quiesce_queue
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait
```
**Symbols:**

```
c079979c-c07997c0: blk_mq_quiesce_queue_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_quiesce_queue_nowait(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000783020)
Location: block/blk-mq.c:219
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_quiesce_queue
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait
```
**Symbols:**

```
c000000000782fc0-c000000000782ffc: blk_mq_quiesce_queue_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_quiesce_queue_nowait(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe00042cc54)
Location: block/blk-mq.c:219
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_quiesce_queue
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait
```
**Symbols:**

```
ffffffe00042cc0e-ffffffe00042cc3a: blk_mq_quiesce_queue_nowait (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_quiesce_queue_nowait(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e6bf5)
Location: block/blk-mq.c:219
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_quiesce_queue
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait
```
**Symbols:**

```
ffffffff814e6bd0-ffffffff814e6be8: blk_mq_quiesce_queue_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_quiesce_queue_nowait(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d7165)
Location: block/blk-mq.c:219
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_quiesce_queue
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait
```
**Symbols:**

```
ffffffff814d7140-ffffffff814d7158: blk_mq_quiesce_queue_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_quiesce_queue_nowait(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e2c85)
Location: block/blk-mq.c:219
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_quiesce_queue
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait
```
**Symbols:**

```
ffffffff814e2c60-ffffffff814e2c78: blk_mq_quiesce_queue_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_quiesce_queue_nowait(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814fbb05)
Location: block/blk-mq.c:219
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_quiesce_queue
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block_nowait
```
**Symbols:**

```
ffffffff814fbae0-ffffffff814fbaf8: blk_mq_quiesce_queue_nowait (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
