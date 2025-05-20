# Function: <code>blk_queue_max_zone_append_sectors</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_queue_max_zone_append_sectors(struct request_queue *q, unsigned int max_zone_append_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81548890)
Location: block/blk-settings.c:231
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
**Symbols:**

```
ffffffff81548890-ffffffff815488d5: blk_queue_max_zone_append_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_queue_max_zone_append_sectors(struct request_queue *q, unsigned int max_zone_append_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81564670)
Location: block/blk-settings.c:235
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
**Symbols:**

```
ffffffff81564670-ffffffff815646b5: blk_queue_max_zone_append_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_queue_max_zone_append_sectors(struct request_queue *q, unsigned int max_zone_append_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff8156cd40)
Location: block/blk-settings.c:208
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
**Symbols:**

```
ffffffff8156cd40-ffffffff8156cd81: blk_queue_max_zone_append_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_queue_max_zone_append_sectors(struct request_queue *q, unsigned int max_zone_append_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff815d1290)
Location: block/blk-settings.c:211
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
**Symbols:**

```
ffffffff815d1290-ffffffff815d12d1: blk_queue_max_zone_append_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_queue_max_zone_append_sectors(struct request_queue *q, unsigned int max_zone_append_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff8167cc90)
Location: block/blk-settings.c:210
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
**Symbols:**

```
ffffffff8167cc90-ffffffff8167cce9: blk_queue_max_zone_append_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_queue_max_zone_append_sectors(struct request_queue *q, unsigned int max_zone_append_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff817396a0)
Location: block/blk-settings.c:210
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
**Symbols:**

```
ffffffff817396a0-ffffffff817396f9: blk_queue_max_zone_append_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_queue_max_zone_append_sectors(struct request_queue *q, unsigned int max_zone_append_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81775d70)
Location: block/blk-settings.c:216
Inline: False
Direct callers:
  - drivers/block/virtio_blk.c:virtblk_probe_zoned_device
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
**Symbols:**

```
ffffffff81775d70-ffffffff81775dc9: blk_queue_max_zone_append_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void blk_queue_max_zone_append_sectors(struct request_queue *q, unsigned int max_zone_append_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-settings.c (0)
Location: block/blk-settings.c:215
Inline: False
Direct callers:
  - drivers/block/virtio_blk.c:virtblk_probe_zoned_device
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
**Symbols:**

```
ffffffff821d2ff0-ffffffff821d3005: blk_queue_max_zone_append_sectors.cold (STB_LOCAL)
ffffffff817b81b0-ffffffff817b8226: blk_queue_max_zone_append_sectors (STB_GLOBAL)
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
