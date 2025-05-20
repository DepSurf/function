# Function: <code>blk_rq_nr_discard_segments</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (0)
Location: include/linux/blkdev.h:1220
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (0)
Location: include/linux/blkdev.h:1235
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81484975)
Location: include/linux/blkdev.h:1270
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-merge.c (ffffffff8148bd9d)
Location: include/linux/blkdev.h:1270
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8149f905)
Location: include/linux/blkdev.h:1095
Inline: True
```
```
In block/blk-merge.c (ffffffff814a59f2)
Location: include/linux/blkdev.h:1095
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cda15)
Location: include/linux/blkdev.h:1109
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-merge.c (ffffffff814d3a1f)
Location: include/linux/blkdev.h:1109
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814e6d35)
Location: include/linux/blkdev.h:1136
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-merge.c (ffffffff814ecd4f)
Location: include/linux/blkdev.h:1136
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81545b05)
Location: include/linux/blkdev.h:1156
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-merge.c (ffffffff8154cb00)
Location: include/linux/blkdev.h:1156
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81567715)
Location: include/linux/blkdev.h:1210
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8156fda5)
Location: include/linux/blkdev.h:1195
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff815d4445)
Location: include/linux/blkdev.h:1169
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81680295)
Location: include/linux/blk-mq.h:1105
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
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
In block/blk-merge.c (ffffffff8173d665)
Location: include/linux/blk-mq.h:1136
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81779be5)
Location: include/linux/blk-mq.h:1136
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
```
```
In drivers/block/virtio_blk.c (ffffffff81b7ec24)
Location: include/linux/blk-mq.h:1136
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff817bbfb5)
Location: include/linux/blk-mq.h:1133
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
```
```
In drivers/block/virtio_blk.c (ffffffff81bd3327)
Location: include/linux/blk-mq.h:1133
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffff8000105e46b4)
Location: include/linux/blkdev.h:1136
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-merge.c (ffff8000105eb580)
Location: include/linux/blkdev.h:1136
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c0791900)
Location: include/linux/blkdev.h:1136
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-merge.c (c0797d2c)
Location: include/linux/blkdev.h:1136
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c00000000077848c)
Location: include/linux/blkdev.h:1136
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-merge.c (c000000000780b4c)
Location: include/linux/blkdev.h:1136
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffe000425e14)
Location: include/linux/blkdev.h:1136
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-merge.c (ffffffe00042b614)
Location: include/linux/blkdev.h:1136
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814df315)
Location: include/linux/blkdev.h:1136
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-merge.c (ffffffff814e532f)
Location: include/linux/blkdev.h:1136
Inline: True
```
```
In drivers/nvme/host/core.c (ffffffff8174499d)
Location: include/linux/blkdev.h:1136
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_setup_discard
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cfcb5)
Location: include/linux/blkdev.h:1136
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-merge.c (ffffffff814d59dd)
Location: include/linux/blkdev.h:1136
Inline: True
```
```
In drivers/nvme/host/core.c (ffffffff8172662d)
Location: include/linux/blkdev.h:1136
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_setup_discard
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814db3a5)
Location: include/linux/blkdev.h:1136
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-merge.c (ffffffff814e13bf)
Location: include/linux/blkdev.h:1136
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814f4215)
Location: include/linux/blkdev.h:1136
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-merge.c (ffffffff814fa271)
Location: include/linux/blkdev.h:1136
Inline: True
```
</details>
</li>
</ul>

## Differences
