# Function: <code>blk_queue_bounce_limit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_bounce_limit(struct request_queue *q, u64 max_addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff813be2e7)
Location: block/blk-settings.c:190
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_make_request
Direct callers:
  - drivers/block/brd.c:brd_alloc
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
  - drivers/md/dm.c:dm_setup_md_queue
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff813be3e0-ffffffff813be45b: blk_queue_bounce_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_bounce_limit(struct request_queue *q, u64 max_addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81402267)
Location: block/blk-settings.c:190
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_make_request
Direct callers:
  - drivers/block/brd.c:brd_alloc
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
  - drivers/md/dm.c:dm_init_normal_md_queue
```
**Symbols:**

```
ffffffff81402360-ffffffff814023db: blk_queue_bounce_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_bounce_limit(struct request_queue *q, u64 max_addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff8141bec7)
Location: block/blk-settings.c:194
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_make_request
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
  - drivers/md/dm.c:dm_init_normal_md_queue
```
**Symbols:**

```
ffffffff8141bfd0-ffffffff8141c04b: blk_queue_bounce_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_queue_bounce_limit(struct request_queue *q, u64 max_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81429f70)
Location: block/blk-settings.c:189
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff81429f70-ffffffff81429fd8: blk_queue_bounce_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_queue_bounce_limit(struct request_queue *q, u64 max_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814551b0)
Location: block/blk-settings.c:190
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff814551b0-ffffffff81455218: blk_queue_bounce_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_queue_bounce_limit(struct request_queue *q, u64 max_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814885a0)
Location: block/blk-settings.c:190
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff814885a0-ffffffff81488608: blk_queue_bounce_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_queue_bounce_limit(struct request_queue *q, u64 max_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814a24c0)
Location: block/blk-settings.c:134
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff814a24c0-ffffffff814a2528: blk_queue_bounce_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_queue_bounce_limit(struct request_queue *q, u64 max_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814d0590)
Location: block/blk-settings.c:135
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff814d0590-ffffffff814d05fc: blk_queue_bounce_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_queue_bounce_limit(struct request_queue *q, u64 max_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814e9910)
Location: block/blk-settings.c:136
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff814e9910-ffffffff814e9976: blk_queue_bounce_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_queue_bounce_limit(struct request_queue *q, u64 max_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81548760)
Location: block/blk-settings.c:102
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff81548760-ffffffff815487c6: blk_queue_bounce_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_queue_bounce_limit(struct request_queue *q, u64 max_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81564530)
Location: block/blk-settings.c:102
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff81564530-ffffffff81564596: blk_queue_bounce_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_queue_bounce_limit(struct request_queue *q, enum blk_bounce bounce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff8156c9a0)
Location: block/blk-settings.c:97
Inline: False
```
**Symbols:**

```
ffffffff8156c9a0-ffffffff8156c9b1: blk_queue_bounce_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_queue_bounce_limit(struct request_queue *q, enum blk_bounce bounce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff815d0ec0)
Location: block/blk-settings.c:98
Inline: False
```
**Symbols:**

```
ffffffff815d0ec0-ffffffff815d0ed1: blk_queue_bounce_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_queue_bounce_limit(struct request_queue *q, enum blk_bounce bounce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff8167c790)
Location: block/blk-settings.c:97
Inline: False
```
**Symbols:**

```
ffffffff8167c790-ffffffff8167c7a9: blk_queue_bounce_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_queue_bounce_limit(struct request_queue *q, enum blk_bounce bounce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81738fc0)
Location: block/blk-settings.c:97
Inline: False
```
**Symbols:**

```
ffffffff81738fc0-ffffffff81738fd9: blk_queue_bounce_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_queue_bounce_limit(struct request_queue *q, enum blk_bounce bounce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff817756a0)
Location: block/blk-settings.c:98
Inline: False
```
**Symbols:**

```
ffffffff817756a0-ffffffff817756b9: blk_queue_bounce_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_queue_bounce_limit(struct request_queue *q, enum blk_bounce bounce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff817b7950)
Location: block/blk-settings.c:98
Inline: False
```
**Symbols:**

```
ffffffff817b7950-ffffffff817b7966: blk_queue_bounce_limit (STB_GLOBAL)
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
void blk_queue_bounce_limit(struct request_queue *q, u64 max_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffff8000105e7718)
Location: block/blk-settings.c:136
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
  - drivers/mmc/core/queue.c:mmc_init_queue
```
**Symbols:**

```
ffff8000105e7718-ffff8000105e7784: blk_queue_bounce_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_queue_bounce_limit(struct request_queue *q, u64 max_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (c07944d8)
Location: block/blk-settings.c:136
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
  - drivers/mmc/core/queue.c:mmc_init_queue
```
**Symbols:**

```
c07944d8-c079452c: blk_queue_bounce_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_queue_bounce_limit(struct request_queue *q, u64 max_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (c00000000077c0b0)
Location: block/blk-settings.c:136
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
c00000000077c0b0-c00000000077c10c: blk_queue_bounce_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_queue_bounce_limit(struct request_queue *q, u64 max_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffe0004284b8)
Location: block/blk-settings.c:136
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
  - drivers/mmc/core/queue.c:mmc_init_queue
```
**Symbols:**

```
ffffffe0004284b8-ffffffe000428522: blk_queue_bounce_limit (STB_GLOBAL)
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
void blk_queue_bounce_limit(struct request_queue *q, u64 max_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814e1ef0)
Location: block/blk-settings.c:136
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff814e1ef0-ffffffff814e1f56: blk_queue_bounce_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_queue_bounce_limit(struct request_queue *q, u64 max_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814d2880)
Location: block/blk-settings.c:136
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff814d2880-ffffffff814d28e6: blk_queue_bounce_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_queue_bounce_limit(struct request_queue *q, u64 max_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814ddf80)
Location: block/blk-settings.c:136
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff814ddf80-ffffffff814ddfe6: blk_queue_bounce_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_queue_bounce_limit(struct request_queue *q, u64 max_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814f6de0)
Location: block/blk-settings.c:136
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff814f6de0-ffffffff814f6e46: blk_queue_bounce_limit (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum blk_bounce bounce</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 max_addr</code>
</li>
</ul>
</details>
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
