# Function: <code>sd_zbc_prepare_zone_append</code>

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
blk_status_t sd_zbc_prepare_zone_append(struct scsi_cmnd *cmd, sector_t *lba, unsigned int nr_blocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81849240)
Location: drivers/scsi/sd_zbc.c:320
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
**Symbols:**

```
ffffffff81849240-ffffffff818493ca: sd_zbc_prepare_zone_append (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
blk_status_t sd_zbc_prepare_zone_append(struct scsi_cmnd *cmd, sector_t *lba, unsigned int nr_blocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff818594e0)
Location: drivers/scsi/sd_zbc.c:321
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
**Symbols:**

```
ffffffff818594e0-ffffffff81859688: sd_zbc_prepare_zone_append (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
blk_status_t sd_zbc_prepare_zone_append(struct scsi_cmnd *cmd, sector_t *lba, unsigned int nr_blocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff8183c1c0)
Location: drivers/scsi/sd_zbc.c:322
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
**Symbols:**

```
ffffffff8183c1c0-ffffffff8183c38b: sd_zbc_prepare_zone_append (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
blk_status_t sd_zbc_prepare_zone_append(struct scsi_cmnd *cmd, sector_t *lba, unsigned int nr_blocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd_zbc.c (0)
Location: drivers/scsi/sd_zbc.c:321
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
**Symbols:**

```
ffffffff81d0d193-ffffffff81d0d20a: sd_zbc_prepare_zone_append.cold (STB_LOCAL)
ffffffff818c8aa0-ffffffff818c8cad: sd_zbc_prepare_zone_append (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
blk_status_t sd_zbc_prepare_zone_append(struct scsi_cmnd *cmd, sector_t *lba, unsigned int nr_blocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd_zbc.c (0)
Location: drivers/scsi/sd_zbc.c:406
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
**Symbols:**

```
ffffffff81ed60d5-ffffffff81ed6144: sd_zbc_prepare_zone_append.cold (STB_LOCAL)
ffffffff81a16000-ffffffff81a16204: sd_zbc_prepare_zone_append (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
blk_status_t sd_zbc_prepare_zone_append(struct scsi_cmnd *cmd, sector_t *lba, unsigned int nr_blocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd_zbc.c (0)
Location: drivers/scsi/sd_zbc.c:409
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
**Symbols:**

```
ffffffff8209c24a-ffffffff8209c2b1: sd_zbc_prepare_zone_append.cold (STB_LOCAL)
ffffffff81b96d50-ffffffff81b96fc9: sd_zbc_prepare_zone_append (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
blk_status_t sd_zbc_prepare_zone_append(struct scsi_cmnd *cmd, sector_t *lba, unsigned int nr_blocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd_zbc.c (0)
Location: drivers/scsi/sd_zbc.c:411
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
**Symbols:**

```
ffffffff8211d18e-ffffffff8211d1f5: sd_zbc_prepare_zone_append.cold (STB_LOCAL)
ffffffff81bed2f0-ffffffff81bed569: sd_zbc_prepare_zone_append (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
blk_status_t sd_zbc_prepare_zone_append(struct scsi_cmnd *cmd, sector_t *lba, unsigned int nr_blocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd_zbc.c (0)
Location: drivers/scsi/sd_zbc.c:411
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
**Symbols:**

```
ffffffff821fb0d3-ffffffff821fb1ab: sd_zbc_prepare_zone_append.cold (STB_LOCAL)
ffffffff81c429c0-ffffffff81c42c68: sd_zbc_prepare_zone_append (STB_GLOBAL)
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
