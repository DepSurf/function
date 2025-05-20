# Function: <code>blk_sync_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_sync_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813b5610)
Location: block/blk-core.c:282
Inline: False
Direct callers:
  - block/blk-core.c:blk_cleanup_queue
  - drivers/md/md.c:mddev_detach
```
**Symbols:**

```
ffffffff813b5610-ffffffff813b568a: blk_sync_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_sync_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fa490)
Location: block/blk-core.c:282
Inline: False
Direct callers:
  - block/blk-core.c:blk_cleanup_queue
  - drivers/md/md.c:mddev_detach
```
**Symbols:**

```
ffffffff813fa490-ffffffff813fa50a: blk_sync_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_sync_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81413e10)
Location: block/blk-core.c:283
Inline: False
Direct callers:
  - block/blk-core.c:blk_cleanup_queue
  - drivers/md/md.c:mddev_detach
```
**Symbols:**

```
ffffffff81413e10-ffffffff81413e8a: blk_sync_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void blk_sync_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81422070)
Location: block/blk-core.c:333
Inline: True
Direct callers:
  - block/blk-core.c:blk_cleanup_queue
  - drivers/md/md.c:mddev_detach
```
**Symbols:**

```
ffffffff81422070-ffffffff814220e0: blk_sync_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void blk_sync_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8144ced0)
Location: block/blk-core.c:333
Inline: True
Direct callers:
  - block/blk-core.c:blk_cleanup_queue
  - drivers/md/md.c:mddev_detach
```
**Symbols:**

```
ffffffff8144ced0-ffffffff8144cf5a: blk_sync_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void blk_sync_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81480140)
Location: block/blk-core.c:405
Inline: True
Direct callers:
  - block/blk-core.c:blk_cleanup_queue
  - drivers/md/md.c:mddev_detach
```
**Symbols:**

```
ffffffff81480140-ffffffff814801ca: blk_sync_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void blk_sync_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8149d1e0)
Location: block/blk-core.c:231
Inline: True
Direct callers:
  - block/blk-core.c:blk_cleanup_queue
  - drivers/md/md.c:mddev_detach
```
**Symbols:**

```
ffffffff8149d1e0-ffffffff8149d24c: blk_sync_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void blk_sync_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cb5c7)
Location: block/blk-core.c:274
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
Direct callers:
  - drivers/md/md.c:mddev_detach
```
**Symbols:**

```
ffffffff814cad80-ffffffff814cada8: blk_sync_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void blk_sync_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814e47b7)
Location: block/blk-core.c:277
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
Direct callers:
  - drivers/md/md.c:mddev_detach
```
**Symbols:**

```
ffffffff814e3f60-ffffffff814e3f88: blk_sync_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void blk_sync_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8154312a)
Location: block/blk-core.c:296
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
Direct callers:
  - drivers/md/md.c:mddev_detach
```
**Symbols:**

```
ffffffff81542970-ffffffff8154299b: blk_sync_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void blk_sync_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8155f97f)
Location: block/blk-core.c:299
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
Direct callers:
  - drivers/md/md.c:mddev_detach
```
**Symbols:**

```
ffffffff8155f010-ffffffff8155f03b: blk_sync_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void blk_sync_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815680bf)
Location: block/blk-core.c:300
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
Direct callers:
  - drivers/md/md.c:mddev_detach
```
**Symbols:**

```
ffffffff81567880-ffffffff815678ab: blk_sync_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void blk_sync_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815cce9b)
Location: block/blk-core.c:295
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
Direct callers:
  - block/genhd.c:del_gendisk
  - drivers/md/md.c:mddev_detach
```
**Symbols:**

```
ffffffff815cc170-ffffffff815cc19b: blk_sync_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void blk_sync_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81678579)
Location: block/blk-core.c:229
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
Direct callers:
  - block/genhd.c:del_gendisk
  - drivers/md/md.c:mddev_detach
```
**Symbols:**

```
ffffffff81678150-ffffffff81678183: blk_sync_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_sync_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81733800)
Location: block/blk-core.c:227
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_destroy_queue
  - block/genhd.c:del_gendisk
  - drivers/md/md.c:mddev_detach
```
**Symbols:**

```
ffffffff81733800-ffffffff81733833: blk_sync_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_sync_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8176fc20)
Location: block/blk-core.c:230
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_destroy_queue
  - block/genhd.c:del_gendisk
  - drivers/md/md.c:mddev_detach
```
**Symbols:**

```
ffffffff8176fc20-ffffffff8176fc53: blk_sync_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_sync_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff817b1e90)
Location: block/blk-core.c:232
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_destroy_queue
  - block/genhd.c:del_gendisk
  - drivers/md/md.c:mddev_detach
```
**Symbols:**

```
ffffffff817b1e90-ffffffff817b1ec3: blk_sync_queue (STB_GLOBAL)
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
void blk_sync_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffff8000105e0f50)
Location: block/blk-core.c:277
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
Direct callers:
  - drivers/md/md.c:mddev_detach
```
**Symbols:**

```
ffff8000105e0168-ffff8000105e019c: blk_sync_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void blk_sync_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c078e428)
Location: block/blk-core.c:277
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
Direct callers:
  - drivers/md/md.c:mddev_detach
```
**Symbols:**

```
c078e2cc-c078e2f8: blk_sync_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void blk_sync_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c000000000774304)
Location: block/blk-core.c:277
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
Direct callers:
  - drivers/md/md.c:mddev_detach
```
**Symbols:**

```
c0000000007740c0-c000000000774110: blk_sync_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void blk_sync_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffe0004236d2)
Location: block/blk-core.c:277
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
Direct callers:
  - drivers/md/md.c:mddev_detach
```
**Symbols:**

```
ffffffe000423562-ffffffe00042359a: blk_sync_queue (STB_GLOBAL)
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
void blk_sync_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814dcd97)
Location: block/blk-core.c:277
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
Direct callers:
  - drivers/nvme/host/core.c:nvme_sync_queues
  - drivers/nvme/host/core.c:nvme_sync_queues
  - drivers/md/md.c:mddev_detach
```
**Symbols:**

```
ffffffff814dc540-ffffffff814dc568: blk_sync_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void blk_sync_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cd747)
Location: block/blk-core.c:277
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
Direct callers:
  - drivers/nvme/host/core.c:nvme_sync_queues
  - drivers/nvme/host/core.c:nvme_sync_queues
  - drivers/md/md.c:mddev_detach
```
**Symbols:**

```
ffffffff814ccef0-ffffffff814ccf18: blk_sync_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void blk_sync_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814d8e27)
Location: block/blk-core.c:277
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
Direct callers:
  - drivers/md/md.c:mddev_detach
```
**Symbols:**

```
ffffffff814d85d0-ffffffff814d85f8: blk_sync_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void blk_sync_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814f1a37)
Location: block/blk-core.c:277
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
Direct callers:
  - drivers/md/md.c:mddev_detach
```
**Symbols:**

```
ffffffff814f11e0-ffffffff814f1208: blk_sync_queue (STB_GLOBAL)
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
