# Function: <code>logical_to_sectors</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff815bdc63)
Location: drivers/scsi/sd.c:2815
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81616afb)
Location: drivers/scsi/sd.h:149
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_getgeo
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
In drivers/scsi/sd.c (ffffffff816465ad)
Location: drivers/scsi/sd.h:161
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_getgeo
```
```
In drivers/scsi/sd_zbc.c (ffffffff81648bf7)
Location: drivers/scsi/sd.h:161
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_write_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
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
In drivers/scsi/sd.c (ffffffff8165b123)
Location: drivers/scsi/sd.h:172
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_getgeo
```
```
In drivers/scsi/sd_zbc.c (ffffffff8165d526)
Location: drivers/scsi/sd.h:172
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_write_lock_zone
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
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
In drivers/scsi/sd.c (ffffffff816c47b5)
Location: drivers/scsi/sd.h:173
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_getgeo
```
```
In drivers/scsi/sd_zbc.c (ffffffff816c6b7c)
Location: drivers/scsi/sd.h:173
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_write_lock_zone
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
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
In drivers/scsi/sd.c (ffffffff81700cd4)
Location: drivers/scsi/sd.h:172
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_getgeo
```
```
In drivers/scsi/sd_zbc.c (ffffffff81702fde)
Location: drivers/scsi/sd.h:172
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
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
In drivers/scsi/sd.c (ffffffff81723da8)
Location: drivers/scsi/sd.h:171
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_getgeo
```
```
In drivers/scsi/sd_zbc.c (ffffffff81725a24)
Location: drivers/scsi/sd.h:171
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
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
In drivers/scsi/sd.c (ffffffff8175efc8)
Location: drivers/scsi/sd.h:171
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81761023)
Location: drivers/scsi/sd.h:171
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
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
In drivers/scsi/sd.c (ffffffff81782fae)
Location: drivers/scsi/sd.h:171
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81784fe3)
Location: drivers/scsi/sd.h:171
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate ⚠️</summary>

```c
sector_t logical_to_sectors(struct scsi_device *sdev, sector_t blocks);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81842100)
Location: drivers/scsi/sd.h:177
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff818483e0)
Location: drivers/scsi/sd.h:177
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_capacity
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_cmnd_checks
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
```
**Symbols:**

```
ffffffff81842100-ffffffff81842116: logical_to_sectors (STB_LOCAL)
ffffffff818483e0-ffffffff818483f6: logical_to_sectors (STB_LOCAL)
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
In drivers/scsi/sd.c (ffffffff81853643)
Location: drivers/scsi/sd.h:180
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81859a8f)
Location: drivers/scsi/sd.h:180
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_capacity
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_cmnd_checks
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
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
In drivers/scsi/sd.c (ffffffff81837063)
Location: drivers/scsi/sd.h:180
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff8183cb06)
Location: drivers/scsi/sd.h:180
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_cmnd_checks
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
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
In drivers/scsi/sd.c (ffffffff818c2f91)
Location: drivers/scsi/sd.h:180
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff818c947c)
Location: drivers/scsi/sd.h:180
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_cmnd_checks
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
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
In drivers/scsi/sd.c (ffffffff81a10d24)
Location: drivers/scsi/sd.h:205
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81a166da)
Location: drivers/scsi/sd.h:205
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_cmnd_checks
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
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
In drivers/scsi/sd.c (ffffffff81b90f7f)
Location: drivers/scsi/sd.h:205
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81b974ea)
Location: drivers/scsi/sd.h:205
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_cmnd_checks
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
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
In drivers/scsi/sd.c (ffffffff81be69f8)
Location: drivers/scsi/sd.h:205
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81beda52)
Location: drivers/scsi/sd.h:205
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_cmnd_checks
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
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
In drivers/scsi/sd.c (ffffffff81c3ca08)
Location: drivers/scsi/sd.h:206
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81c43180)
Location: drivers/scsi/sd.h:206
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_cmnd_checks
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
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
In drivers/scsi/sd.c (ffff800010989b6c)
Location: drivers/scsi/sd.h:171
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffff80001098bb24)
Location: drivers/scsi/sd.h:171
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
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
In drivers/scsi/sd.c (c0a5bc5c)
Location: drivers/scsi/sd.h:171
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sd_zbc.c (c0a5dee4)
Location: drivers/scsi/sd.h:171
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
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
In drivers/scsi/sd.c (c000000000a49e9c)
Location: drivers/scsi/sd.h:171
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sd_zbc.c (c000000000a4c870)
Location: drivers/scsi/sd.h:171
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
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
In drivers/scsi/sd.c (ffffffe0005edd5a)
Location: drivers/scsi/sd.h:171
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_getgeo
```
```
In drivers/scsi/sd_zbc.c (ffffffe0005f01b4)
Location: drivers/scsi/sd.h:171
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
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
In drivers/scsi/sd.c (ffffffff8173769e)
Location: drivers/scsi/sd.h:171
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff817396d3)
Location: drivers/scsi/sd.h:171
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
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
In drivers/scsi/sd.c (ffffffff8171933e)
Location: drivers/scsi/sd.h:171
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff8171b373)
Location: drivers/scsi/sd.h:171
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
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
In drivers/scsi/sd.c (ffffffff81777e2e)
Location: drivers/scsi/sd.h:171
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81779e63)
Location: drivers/scsi/sd.h:171
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
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
In drivers/scsi/sd.c (ffffffff81791c4e)
Location: drivers/scsi/sd.h:171
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_getgeo
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81793c93)
Location: drivers/scsi/sd.h:171
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
