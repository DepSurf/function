# Function: <code>blk_queue_max_write_zeroes_sectors</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_queue_max_write_zeroes_sectors(struct request_queue *q, unsigned int max_write_zeroes_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff8141bc80)
Location: block/blk-settings.c:311
Inline: False
```
**Symbols:**

```
ffffffff8141bc80-ffffffff8141bc91: blk_queue_max_write_zeroes_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_queue_max_write_zeroes_sectors(struct request_queue *q, unsigned int max_write_zeroes_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81429c20)
Location: block/blk-settings.c:306
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/scsi/sd.c:sd_config_write_same
```
**Symbols:**

```
ffffffff81429c20-ffffffff81429c31: blk_queue_max_write_zeroes_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_queue_max_write_zeroes_sectors(struct request_queue *q, unsigned int max_write_zeroes_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81454de0)
Location: block/blk-settings.c:307
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/scsi/sd.c:sd_config_write_same
```
**Symbols:**

```
ffffffff81454de0-ffffffff81454df1: blk_queue_max_write_zeroes_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_queue_max_write_zeroes_sectors(struct request_queue *q, unsigned int max_write_zeroes_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81488250)
Location: block/blk-settings.c:307
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/scsi/sd.c:sd_config_write_same
```
**Symbols:**

```
ffffffff81488250-ffffffff81488261: blk_queue_max_write_zeroes_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_queue_max_write_zeroes_sectors(struct request_queue *q, unsigned int max_write_zeroes_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814a2270)
Location: block/blk-settings.c:251
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/scsi/sd.c:sd_config_write_same
```
**Symbols:**

```
ffffffff814a2270-ffffffff814a2281: blk_queue_max_write_zeroes_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_queue_max_write_zeroes_sectors(struct request_queue *q, unsigned int max_write_zeroes_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814d0350)
Location: block/blk-settings.c:252
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/scsi/sd.c:sd_config_write_same
```
**Symbols:**

```
ffffffff814d0350-ffffffff814d0361: blk_queue_max_write_zeroes_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_queue_max_write_zeroes_sectors(struct request_queue *q, unsigned int max_write_zeroes_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814e96b0)
Location: block/blk-settings.c:253
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/scsi/sd.c:sd_config_write_same
```
**Symbols:**

```
ffffffff814e96b0-ffffffff814e96c1: blk_queue_max_write_zeroes_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_queue_max_write_zeroes_sectors(struct request_queue *q, unsigned int max_write_zeroes_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81548540)
Location: block/blk-settings.c:219
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/scsi/sd.c:sd_config_write_same
```
**Symbols:**

```
ffffffff81548540-ffffffff81548551: blk_queue_max_write_zeroes_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_queue_max_write_zeroes_sectors(struct request_queue *q, unsigned int max_write_zeroes_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff815642a0)
Location: block/blk-settings.c:223
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/scsi/sd.c:sd_config_write_same
```
**Symbols:**

```
ffffffff815642a0-ffffffff815642b1: blk_queue_max_write_zeroes_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_queue_max_write_zeroes_sectors(struct request_queue *q, unsigned int max_write_zeroes_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff8156ca20)
Location: block/blk-settings.c:196
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_config_discard
  - drivers/block/loop.c:loop_config_discard
  - drivers/scsi/sd.c:sd_config_write_same
```
**Symbols:**

```
ffffffff8156ca20-ffffffff8156ca31: blk_queue_max_write_zeroes_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_queue_max_write_zeroes_sectors(struct request_queue *q, unsigned int max_write_zeroes_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff815d0f40)
Location: block/blk-settings.c:199
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_config_discard
  - drivers/block/loop.c:loop_config_discard
  - drivers/scsi/sd.c:sd_config_write_same
```
**Symbols:**

```
ffffffff815d0f40-ffffffff815d0f51: blk_queue_max_write_zeroes_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_queue_max_write_zeroes_sectors(struct request_queue *q, unsigned int max_write_zeroes_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff8167c820)
Location: block/blk-settings.c:198
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_config_write_same
```
**Symbols:**

```
ffffffff8167c820-ffffffff8167c839: blk_queue_max_write_zeroes_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_queue_max_write_zeroes_sectors(struct request_queue *q, unsigned int max_write_zeroes_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81739090)
Location: block/blk-settings.c:198
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_config_write_same
```
**Symbols:**

```
ffffffff81739090-ffffffff817390a9: blk_queue_max_write_zeroes_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_queue_max_write_zeroes_sectors(struct request_queue *q, unsigned int max_write_zeroes_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81775760)
Location: block/blk-settings.c:204
Inline: False
Direct callers:
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/scsi/sd.c:sd_config_write_same
```
**Symbols:**

```
ffffffff81775760-ffffffff81775779: blk_queue_max_write_zeroes_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_queue_max_write_zeroes_sectors(struct request_queue *q, unsigned int max_write_zeroes_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff817b7a10)
Location: block/blk-settings.c:203
Inline: False
Direct callers:
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/scsi/sd.c:sd_config_write_same
```
**Symbols:**

```
ffffffff817b7a10-ffffffff817b7a29: blk_queue_max_write_zeroes_sectors (STB_GLOBAL)
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
void blk_queue_max_write_zeroes_sectors(struct request_queue *q, unsigned int max_write_zeroes_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffff8000105e77e8)
Location: block/blk-settings.c:253
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/scsi/sd.c:sd_config_write_same
```
**Symbols:**

```
ffff8000105e77e8-ffff8000105e7814: blk_queue_max_write_zeroes_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_queue_max_write_zeroes_sectors(struct request_queue *q, unsigned int max_write_zeroes_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (c079428c)
Location: block/blk-settings.c:253
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/scsi/sd.c:sd_config_write_same
```
**Symbols:**

```
c079428c-c07942a8: blk_queue_max_write_zeroes_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_queue_max_write_zeroes_sectors(struct request_queue *q, unsigned int max_write_zeroes_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (c00000000077c140)
Location: block/blk-settings.c:253
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/scsi/sd.c:sd_config_write_same
  - drivers/scsi/sd.c:sd_config_write_same
  - drivers/scsi/sd.c:sd_config_write_same
  - drivers/scsi/sd.c:sd_config_write_same
```
**Symbols:**

```
c00000000077c140-c00000000077c150: blk_queue_max_write_zeroes_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_queue_max_write_zeroes_sectors(struct request_queue *q, unsigned int max_write_zeroes_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffe00042857a)
Location: block/blk-settings.c:253
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/scsi/sd.c:sd_config_write_same
```
**Symbols:**

```
ffffffe00042857a-ffffffe0004285a4: blk_queue_max_write_zeroes_sectors (STB_GLOBAL)
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
void blk_queue_max_write_zeroes_sectors(struct request_queue *q, unsigned int max_write_zeroes_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814e1c90)
Location: block/blk-settings.c:253
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/scsi/sd.c:sd_config_write_same
  - drivers/nvme/host/core.c:nvme_update_disk_info
  - drivers/nvme/host/core.c:nvme_update_disk_info
```
**Symbols:**

```
ffffffff814e1c90-ffffffff814e1ca1: blk_queue_max_write_zeroes_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_queue_max_write_zeroes_sectors(struct request_queue *q, unsigned int max_write_zeroes_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814d2620)
Location: block/blk-settings.c:253
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/scsi/sd.c:sd_config_write_same
  - drivers/nvme/host/core.c:nvme_update_disk_info
  - drivers/nvme/host/core.c:nvme_update_disk_info
```
**Symbols:**

```
ffffffff814d2620-ffffffff814d2631: blk_queue_max_write_zeroes_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_queue_max_write_zeroes_sectors(struct request_queue *q, unsigned int max_write_zeroes_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814ddd20)
Location: block/blk-settings.c:253
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/scsi/sd.c:sd_config_write_same
```
**Symbols:**

```
ffffffff814ddd20-ffffffff814ddd31: blk_queue_max_write_zeroes_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_queue_max_write_zeroes_sectors(struct request_queue *q, unsigned int max_write_zeroes_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814f6b80)
Location: block/blk-settings.c:253
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/scsi/sd.c:sd_config_write_same
```
**Symbols:**

```
ffffffff814f6b80-ffffffff814f6b91: blk_queue_max_write_zeroes_sectors (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
