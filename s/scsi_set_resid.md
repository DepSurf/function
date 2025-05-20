# Function: <code>scsi_set_resid</code>

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
In drivers/scsi/scsi_lib.c (ffffffff815ae46b)
Location: include/scsi/scsi_cmnd.h:186
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff815ba9af)
Location: include/scsi/scsi_cmnd.h:186
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
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
In drivers/scsi/scsi_lib.c (ffffffff816067fb)
Location: include/scsi/scsi_cmnd.h:186
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff81613019)
Location: include/scsi/scsi_cmnd.h:186
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
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
In drivers/scsi/scsi_lib.c (ffffffff81635d1b)
Location: include/scsi/scsi_cmnd.h:186
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff81643263)
Location: include/scsi/scsi_cmnd.h:186
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
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
In drivers/scsi/scsi_lib.c (ffffffff8164af6b)
Location: include/scsi/scsi_cmnd.h:191
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff81659723)
Location: include/scsi/scsi_cmnd.h:191
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
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
In drivers/scsi/scsi_lib.c (ffffffff816b42bb)
Location: include/scsi/scsi_cmnd.h:197
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff816c40f3)
Location: include/scsi/scsi_cmnd.h:197
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
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
In drivers/scsi/scsi_lib.c (ffffffff816f034d)
Location: include/scsi/scsi_cmnd.h:200
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff81700653)
Location: include/scsi/scsi_cmnd.h:200
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
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
In drivers/scsi/scsi_lib.c (ffffffff8171547f)
Location: include/scsi/scsi_cmnd.h:203
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/sd.c (ffffffff81723457)
Location: include/scsi/scsi_cmnd.h:203
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
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
In drivers/scsi/scsi_lib.c (ffffffff81750cfb)
Location: include/scsi/scsi_cmnd.h:192
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/sd.c (ffffffff8175ea59)
Location: include/scsi/scsi_cmnd.h:192
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
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
In drivers/scsi/scsi_lib.c (ffffffff81774f48)
Location: include/scsi/scsi_cmnd.h:193
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/sd.c (ffffffff817829ee)
Location: include/scsi/scsi_cmnd.h:193
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
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
In drivers/scsi/scsi_lib.c (ffffffff81837fea)
Location: include/scsi/scsi_cmnd.h:193
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/sd.c (ffffffff8184602e)
Location: include/scsi/scsi_cmnd.h:193
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
```
```
In drivers/scsi/sd_zbc.c (ffffffff81848b81)
Location: include/scsi/scsi_cmnd.h:193
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
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
In drivers/scsi/scsi_lib.c (ffffffff818488f6)
Location: include/scsi/scsi_cmnd.h:194
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/sd.c (ffffffff818560b9)
Location: include/scsi/scsi_cmnd.h:194
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
```
```
In drivers/scsi/sd_zbc.c (ffffffff81859067)
Location: include/scsi/scsi_cmnd.h:194
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
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
In drivers/scsi/scsi_lib.c (ffffffff8182bca4)
Location: include/scsi/scsi_cmnd.h:196
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/sd.c (ffffffff81838e65)
Location: include/scsi/scsi_cmnd.h:196
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
```
```
In drivers/scsi/sd_zbc.c (ffffffff8183bd4e)
Location: include/scsi/scsi_cmnd.h:196
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
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
In drivers/scsi/scsi_lib.c (ffffffff818b7866)
Location: include/scsi/scsi_cmnd.h:200
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/sd.c (ffffffff818c54ca)
Location: include/scsi/scsi_cmnd.h:200
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
```
```
In drivers/scsi/sd_zbc.c (ffffffff818c8669)
Location: include/scsi/scsi_cmnd.h:200
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
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
In drivers/scsi/scsi_lib.c (ffffffff81a02fd1)
Location: include/scsi/scsi_cmnd.h:190
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/sd.c (ffffffff81a11fdd)
Location: include/scsi/scsi_cmnd.h:190
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
```
```
In drivers/scsi/sd_zbc.c (ffffffff81a156b9)
Location: include/scsi/scsi_cmnd.h:190
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
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
In drivers/scsi/scsi_lib.c (ffffffff81b81945)
Location: include/scsi/scsi_cmnd.h:191
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/sd.c (ffffffff81b922cd)
Location: include/scsi/scsi_cmnd.h:191
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
```
```
In drivers/scsi/sd_zbc.c (ffffffff81b960ed)
Location: include/scsi/scsi_cmnd.h:191
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
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
In drivers/scsi/scsi_lib.c (ffffffff81bd564e)
Location: include/scsi/scsi_cmnd.h:196
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/virtio_scsi.c (ffffffff81be21ea)
Location: include/scsi/scsi_cmnd.h:196
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_complete_cmd
```
```
In drivers/scsi/sd.c (ffffffff81be86f3)
Location: include/scsi/scsi_cmnd.h:196
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
```
```
In drivers/scsi/sd_zbc.c (ffffffff81bec8ec)
Location: include/scsi/scsi_cmnd.h:196
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
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
In drivers/scsi/scsi_lib.c (ffffffff81c2a2a6)
Location: include/scsi/scsi_cmnd.h:196
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/virtio_scsi.c (ffffffff81c3730a)
Location: include/scsi/scsi_cmnd.h:196
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_complete_cmd
```
```
In drivers/scsi/sd.c (ffffffff81c3dc51)
Location: include/scsi/scsi_cmnd.h:196
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
```
```
In drivers/scsi/sd_zbc.c (ffffffff81c41fe2)
Location: include/scsi/scsi_cmnd.h:196
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
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
In drivers/scsi/scsi_lib.c (ffff800010979110)
Location: include/scsi/scsi_cmnd.h:193
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/sd.c (ffff800010989648)
Location: include/scsi/scsi_cmnd.h:193
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
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
In drivers/scsi/scsi_lib.c (c0a4cedc)
Location: include/scsi/scsi_cmnd.h:193
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/sd.c (c0a5b7b4)
Location: include/scsi/scsi_cmnd.h:193
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
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
In drivers/scsi/scsi_lib.c (c000000000a338bc)
Location: include/scsi/scsi_cmnd.h:193
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/sd.c (c000000000a49834)
Location: include/scsi/scsi_cmnd.h:193
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
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
In drivers/scsi/scsi_lib.c (ffffffe0005e08dc)
Location: include/scsi/scsi_cmnd.h:193
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/sd.c (ffffffe0005ed908)
Location: include/scsi/scsi_cmnd.h:193
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
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
In drivers/scsi/scsi_lib.c (ffffffff81729638)
Location: include/scsi/scsi_cmnd.h:193
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/sd.c (ffffffff817370de)
Location: include/scsi/scsi_cmnd.h:193
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
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
In drivers/scsi/scsi_lib.c (ffffffff81702a4a)
Location: include/scsi/scsi_cmnd.h:193
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/storvsc_drv.c (ffffffff8171344e)
Location: include/scsi/scsi_cmnd.h:193
Inline: True
Inline callers:
  - drivers/scsi/storvsc_drv.c:storvsc_on_channel_callback
```
```
In drivers/scsi/sd.c (ffffffff81718d7e)
Location: include/scsi/scsi_cmnd.h:193
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
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
In drivers/scsi/scsi_lib.c (ffffffff81768408)
Location: include/scsi/scsi_cmnd.h:193
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/virtio_scsi.c (ffffffff8177215c)
Location: include/scsi/scsi_cmnd.h:193
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_complete_cmd
```
```
In drivers/scsi/sd.c (ffffffff8177786e)
Location: include/scsi/scsi_cmnd.h:193
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
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
In drivers/scsi/scsi_lib.c (ffffffff81783b28)
Location: include/scsi/scsi_cmnd.h:193
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/sd.c (ffffffff8179168e)
Location: include/scsi/scsi_cmnd.h:193
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
```
</details>
</li>
</ul>

## Differences
