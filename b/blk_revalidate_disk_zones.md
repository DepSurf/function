# Function: <code>blk_revalidate_disk_zones</code>

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
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int blk_revalidate_disk_zones(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-zoned.c (0)
Location: block/blk-zoned.c:410
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff814cc25e-ffffffff814cc2cb: blk_revalidate_disk_zones.cold.14 (STB_LOCAL)
ffffffff814cbb30-ffffffff814cbf22: blk_revalidate_disk_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int blk_revalidate_disk_zones(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-zoned.c (0)
Location: block/blk-zoned.c:414
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff814fab11-ffffffff814fab31: blk_revalidate_disk_zones.cold (STB_LOCAL)
ffffffff814fa3d0-ffffffff814fa718: blk_revalidate_disk_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int blk_revalidate_disk_zones(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81518330)
Location: block/blk-zoned.c:453
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff81518330-ffffffff8151867b: blk_revalidate_disk_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int blk_revalidate_disk_zones(struct gendisk *disk, void (*update_driver_data)(struct gendisk *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-zoned.c (0)
Location: block/blk-zoned.c:485
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
**Symbols:**

```
ffffffff8157914d-ffffffff8157916a: blk_revalidate_disk_zones.cold (STB_LOCAL)
ffffffff81578f30-ffffffff815790c8: blk_revalidate_disk_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int blk_revalidate_disk_zones(struct gendisk *disk, void (*update_driver_data)(struct gendisk *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-zoned.c (0)
Location: block/blk-zoned.c:520
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
**Symbols:**

```
ffffffff81bf3e50-ffffffff81bf3ec3: blk_revalidate_disk_zones.cold (STB_LOCAL)
ffffffff815959e0-ffffffff81595bb6: blk_revalidate_disk_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int blk_revalidate_disk_zones(struct gendisk *disk, void (*update_driver_data)(struct gendisk *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-zoned.c (0)
Location: block/blk-zoned.c:512
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
**Symbols:**

```
ffffffff81be5cb2-ffffffff81be5d1d: blk_revalidate_disk_zones.cold (STB_LOCAL)
ffffffff8159c780-ffffffff8159c94f: blk_revalidate_disk_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int blk_revalidate_disk_zones(struct gendisk *disk, void (*update_driver_data)(struct gendisk *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-zoned.c (0)
Location: block/blk-zoned.c:566
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
**Symbols:**

```
ffffffff81cda49c-ffffffff81cda507: blk_revalidate_disk_zones.cold (STB_LOCAL)
ffffffff81604e30-ffffffff81604fff: blk_revalidate_disk_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int blk_revalidate_disk_zones(struct gendisk *disk, void (*update_driver_data)(struct gendisk *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-zoned.c (0)
Location: block/blk-zoned.c:559
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
**Symbols:**

```
ffffffff81e8e059-ffffffff81e8e0af: blk_revalidate_disk_zones.cold (STB_LOCAL)
ffffffff816b8600-ffffffff816b87ee: blk_revalidate_disk_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int blk_revalidate_disk_zones(struct gendisk *disk, void (*update_driver_data)(struct gendisk *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81777fa0)
Location: block/blk-zoned.c:554
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
**Symbols:**

```
ffffffff81777fa0-ffffffff81778203: blk_revalidate_disk_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int blk_revalidate_disk_zones(struct gendisk *disk, void (*update_driver_data)(struct gendisk *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-zoned.c (0)
Location: block/blk-zoned.c:535
Inline: False
Direct callers:
  - drivers/block/virtio_blk.c:virtblk_config_changed_work
  - drivers/block/virtio_blk.c:virtblk_probe_zoned_device
  - drivers/block/virtio_blk.c:virtblk_probe_zoned_device
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
**Symbols:**

```
ffffffff820f732a-ffffffff820f7347: blk_revalidate_disk_zones.cold (STB_LOCAL)
ffffffff817b7e80-ffffffff817b8157: blk_revalidate_disk_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int blk_revalidate_disk_zones(struct gendisk *disk, void (*update_driver_data)(struct gendisk *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-zoned.c (0)
Location: block/blk-zoned.c:535
Inline: False
Direct callers:
  - drivers/block/virtio_blk.c:virtblk_probe_zoned_device
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
**Symbols:**

```
ffffffff821d4b31-ffffffff821d4b6b: blk_revalidate_disk_zones.cold (STB_LOCAL)
ffffffff817fc550-ffffffff817fc83b: blk_revalidate_disk_zones (STB_GLOBAL)
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
int blk_revalidate_disk_zones(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffff80001061fcd0)
Location: block/blk-zoned.c:453
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffff80001061fcd0-ffff80001061ffe0: blk_revalidate_disk_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int blk_revalidate_disk_zones(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (c07c77d4)
Location: block/blk-zoned.c:453
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
c07c77d4-c07c7b50: blk_revalidate_disk_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int blk_revalidate_disk_zones(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (c0000000007bf2c0)
Location: block/blk-zoned.c:453
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
c0000000007bf2c0-c0000000007bf6f4: blk_revalidate_disk_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int blk_revalidate_disk_zones(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffe00045246e)
Location: block/blk-zoned.c:453
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffe00045246e-ffffffe000452760: blk_revalidate_disk_zones (STB_GLOBAL)
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
int blk_revalidate_disk_zones(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81510910)
Location: block/blk-zoned.c:453
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff81510910-ffffffff81510c5b: blk_revalidate_disk_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int blk_revalidate_disk_zones(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81500c30)
Location: block/blk-zoned.c:453
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff81500c30-ffffffff81500f7b: blk_revalidate_disk_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int blk_revalidate_disk_zones(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff8150c9a0)
Location: block/blk-zoned.c:453
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff8150c9a0-ffffffff8150cceb: blk_revalidate_disk_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int blk_revalidate_disk_zones(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81526080)
Location: block/blk-zoned.c:453
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff81526080-ffffffff815263cb: blk_revalidate_disk_zones (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void (*update_driver_data)(struct gendisk *)</code>
</li>
</ul>
</details>
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
