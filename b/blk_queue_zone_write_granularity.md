# Function: <code>blk_queue_zone_write_granularity</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_queue_zone_write_granularity(struct request_queue *q, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff8156cdd0)
Location: block/blk-settings.c:351
Inline: False
Direct callers:
  - block/blk-settings.c:blk_queue_set_zoned
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
**Symbols:**

```
ffffffff8156cdd0-ffffffff8156cdfe: blk_queue_zone_write_granularity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_zone_write_granularity(struct request_queue *q, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff815d1b20)
Location: block/blk-settings.c:354
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_set_zoned
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
**Symbols:**

```
ffffffff815d1320-ffffffff815d134e: blk_queue_zone_write_granularity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_zone_write_granularity(struct request_queue *q, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff8167d5f8)
Location: block/blk-settings.c:353
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_set_zoned
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
**Symbols:**

```
ffffffff8167cd50-ffffffff8167cd92: blk_queue_zone_write_granularity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_zone_write_granularity(struct request_queue *q, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff8173a10e)
Location: block/blk-settings.c:353
Inline: True
Inline callers:
  - block/blk-settings.c:disk_set_zoned
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
**Symbols:**

```
ffffffff817397a0-ffffffff817397e2: blk_queue_zone_write_granularity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_zone_write_granularity(struct request_queue *q, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff817767fe)
Location: block/blk-settings.c:359
Inline: True
Inline callers:
  - block/blk-settings.c:disk_set_zoned
Direct callers:
  - drivers/scsi/sd.c:sd_read_block_characteristics
```
**Symbols:**

```
ffffffff81775e70-ffffffff81775eb2: blk_queue_zone_write_granularity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void blk_queue_zone_write_granularity(struct request_queue *q, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-settings.c (ffffffff817b89fd)
Location: block/blk-settings.c:362
Inline: True
Inline callers:
  - block/blk-settings.c:disk_set_zoned
Direct callers:
  - drivers/scsi/sd.c:sd_read_block_characteristics
```
**Symbols:**

```
ffffffff821d3005-ffffffff821d301a: blk_queue_zone_write_granularity.cold (STB_LOCAL)
ffffffff817b8240-ffffffff817b82a3: blk_queue_zone_write_granularity (STB_GLOBAL)
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
