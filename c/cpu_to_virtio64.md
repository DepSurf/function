# Function: <code>cpu_to_virtio64</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/virtio_config.h:240
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/virtio_config.h:240
Inline: True
```
```
In drivers/block/virtio_blk.c (0)
Location: include/linux/virtio_config.h:240
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/virtio_config.h:253
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/virtio_config.h:253
Inline: True
```
```
In drivers/block/virtio_blk.c (0)
Location: include/linux/virtio_config.h:253
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/virtio_config.h:253
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/virtio_config.h:253
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/virtio_config.h:278
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/virtio_config.h:278
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/virtio_config.h:279
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/virtio_config.h:279
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
In drivers/virtio/virtio_ring.c (ffffffff815ec0ae)
Location: include/linux/virtio_config.h:279
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
```
```
In drivers/virtio/virtio_balloon.c (ffffffff815f0346)
Location: include/linux/virtio_config.h:279
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In drivers/virtio/virtio_ring.c (ffffffff816065b4)
Location: include/linux/virtio_config.h:285
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add
  - drivers/virtio/virtio_ring.c:virtqueue_add
  - drivers/virtio/virtio_ring.c:virtqueue_add
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8160a926)
Location: include/linux/virtio_config.h:285
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In drivers/virtio/virtio_ring.c (ffffffff8163a3c5)
Location: include/linux/virtio_config.h:285
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8163e726)
Location: include/linux/virtio_config.h:285
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In drivers/virtio/virtio_ring.c (ffffffff8165c61e)
Location: include/linux/virtio_config.h:285
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81660c96)
Location: include/linux/virtio_config.h:285
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In drivers/virtio/virtio_ring.c (ffffffff8170ac7c)
Location: include/linux/virtio_config.h:285
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81710003)
Location: include/linux/virtio_config.h:285
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81727acc)
Location: include/linux/virtio_config.h:303
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8172ccf3)
Location: include/linux/virtio_config.h:303
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8170b564)
Location: include/linux/virtio_config.h:303
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
```
```
In drivers/virtio/virtio_balloon.c (ffffffff817108c3)
Location: include/linux/virtio_config.h:303
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff817876c5)
Location: include/linux/virtio_config.h:304
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8178d2b3)
Location: include/linux/virtio_config.h:304
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff818be864)
Location: include/linux/virtio_config.h:351
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
```
```
In drivers/virtio/virtio_balloon.c (ffffffff818c545b)
Location: include/linux/virtio_config.h:351
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81a0de34)
Location: include/linux/virtio_config.h:365
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a15d4b)
Location: include/linux/virtio_config.h:365
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In drivers/virtio/virtio_ring.c (ffffffff81a56d7f)
Location: include/linux/virtio_config.h:367
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a5edfb)
Location: include/linux/virtio_config.h:367
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
```
In drivers/block/virtio_blk.c (ffffffff81b7f0cf)
Location: include/linux/virtio_config.h:367
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_report_zones
```
```
In drivers/scsi/virtio_scsi.c (ffffffff81be2e07)
Location: include/linux/virtio_config.h:367
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_abort
  - drivers/scsi/virtio_scsi.c:virtscsi_queuecommand
  - drivers/scsi/virtio_scsi.c:virtscsi_queuecommand
```
```
In drivers/net/virtio_net.c (ffffffff81c4d83c)
Location: include/linux/virtio_config.h:367
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
In drivers/virtio/virtio_ring.c (ffffffff81aa8177)
Location: include/linux/virtio_config.h:371
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81ab155b)
Location: include/linux/virtio_config.h:371
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
```
In drivers/block/virtio_blk.c (ffffffff81bd2f3f)
Location: include/linux/virtio_config.h:371
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_report_zones
```
```
In drivers/scsi/virtio_scsi.c (ffffffff81c37fd7)
Location: include/linux/virtio_config.h:371
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_abort
  - drivers/scsi/virtio_scsi.c:virtscsi_queuecommand
  - drivers/scsi/virtio_scsi.c:virtscsi_queuecommand
```
```
In drivers/net/virtio_net.c (ffffffff81d02f8c)
Location: include/linux/virtio_config.h:371
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
In drivers/virtio/virtio_ring.c (ffff80001082557c)
Location: include/linux/virtio_config.h:285
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
```
```
In drivers/virtio/virtio_balloon.c (ffff8000108299ac)
Location: include/linux/virtio_config.h:285
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In drivers/virtio/virtio_ring.c (c09420e0)
Location: include/linux/virtio_config.h:285
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
```
```
In drivers/virtio/virtio_balloon.c (c0947b9c)
Location: include/linux/virtio_config.h:285
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In drivers/virtio/virtio_ring.c (c0000000008cfde8)
Location: include/linux/virtio_config.h:285
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
```
```
In drivers/virtio/virtio_balloon.c (c0000000008d7a98)
Location: include/linux/virtio_config.h:285
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In drivers/virtio/virtio_ring.c (ffffffe00051a558)
Location: include/linux/virtio_config.h:285
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
```
```
In drivers/virtio/virtio_balloon.c (ffffffe000520656)
Location: include/linux/virtio_config.h:285
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In drivers/virtio/virtio_ring.c (ffffffff816224be)
Location: include/linux/virtio_config.h:285
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81626b06)
Location: include/linux/virtio_config.h:285
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In drivers/virtio/virtio_ring.c (ffffffff81616b0e)
Location: include/linux/virtio_config.h:285
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8161b186)
Location: include/linux/virtio_config.h:285
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In drivers/virtio/virtio_ring.c (ffffffff8165045e)
Location: include/linux/virtio_config.h:285
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81654ad6)
Location: include/linux/virtio_config.h:285
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
```
In drivers/scsi/virtio_scsi.c (ffffffff817724f8)
Location: include/linux/virtio_config.h:285
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_abort
  - drivers/scsi/virtio_scsi.c:virtscsi_queuecommand
  - drivers/scsi/virtio_scsi.c:virtscsi_queuecommand
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
In drivers/virtio/virtio_ring.c (ffffffff8166aaee)
Location: include/linux/virtio_config.h:285
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8166f4a6)
Location: include/linux/virtio_config.h:285
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
</details>
</li>
</ul>

## Differences
