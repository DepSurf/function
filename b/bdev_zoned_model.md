# Function: <code>bdev_zoned_model</code>

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
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (0)
Location: include/linux/blkdev.h:1557
Inline: True
```
```
In drivers/md/dm-kcopyd.c (ffffffff8175800c)
Location: include/linux/blkdev.h:1557
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In drivers/md/dm-table.c (ffffffff817c28da)
Location: include/linux/blkdev.h:1572
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_area_is_invalid
```
```
In drivers/md/dm-kcopyd.c (ffffffff817ca27c)
Location: include/linux/blkdev.h:1572
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In drivers/md/dm-table.c (ffffffff8180b00a)
Location: include/linux/blkdev.h:1613
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_area_is_invalid
```
```
In drivers/md/dm-kcopyd.c (ffffffff8181307f)
Location: include/linux/blkdev.h:1613
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In drivers/md/dm-table.c (ffffffff81837007)
Location: include/linux/blkdev.h:1392
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_area_is_invalid
```
```
In drivers/md/dm-kcopyd.c (ffffffff8183f04f)
Location: include/linux/blkdev.h:1392
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In drivers/md/dm-table.c (ffffffff81879c08)
Location: include/linux/blkdev.h:1406
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_area_is_invalid
```
```
In drivers/md/dm-kcopyd.c (ffffffff81881d84)
Location: include/linux/blkdev.h:1406
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In drivers/md/dm-table.c (ffffffff818ab9f8)
Location: include/linux/blkdev.h:1433
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_area_is_invalid
```
```
In drivers/md/dm-kcopyd.c (ffffffff818b3c24)
Location: include/linux/blkdev.h:1433
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In drivers/md/dm-table.c (ffffffff8197bd07)
Location: include/linux/blkdev.h:1467
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_area_is_invalid
```
```
In drivers/md/dm-kcopyd.c (ffffffff81984ac4)
Location: include/linux/blkdev.h:1467
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In drivers/md/dm-table.c (ffffffff81980627)
Location: include/linux/blkdev.h:1567
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_area_is_invalid
```
```
In drivers/md/dm-kcopyd.c (ffffffff81988b64)
Location: include/linux/blkdev.h:1567
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In drivers/md/dm-table.c (ffffffff81964853)
Location: include/linux/blkdev.h:1564
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_area_is_invalid
```
```
In drivers/md/dm-kcopyd.c (ffffffff8196d244)
Location: include/linux/blkdev.h:1564
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In drivers/md/dm-kcopyd.c (ffffffff81a1531c)
Location: include/linux/blkdev.h:1555
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In drivers/md/dm-kcopyd.c (ffffffff81b7e168)
Location: include/linux/blkdev.h:1321
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In drivers/md/dm-kcopyd.c (ffffffff81d1c170)
Location: include/linux/blkdev.h:1274
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-kcopyd.c (ffffffff81d852ec)
Location: include/linux/blkdev.h:1261
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In drivers/md/dm-table.c (ffff800010b02304)
Location: include/linux/blkdev.h:1433
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_area_is_invalid
```
```
In drivers/md/dm-kcopyd.c (ffff800010b0bcb0)
Location: include/linux/blkdev.h:1433
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In drivers/md/dm-table.c (c0be1728)
Location: include/linux/blkdev.h:1433
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_area_is_invalid
```
```
In drivers/md/dm-kcopyd.c (c0be972c)
Location: include/linux/blkdev.h:1433
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In drivers/md/dm-table.c (c000000000bf11d0)
Location: include/linux/blkdev.h:1433
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_area_is_invalid
```
```
In drivers/md/dm-kcopyd.c (c000000000bfd8d0)
Location: include/linux/blkdev.h:1433
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In drivers/md/dm-table.c (ffffffe0006f1bea)
Location: include/linux/blkdev.h:1433
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_area_is_invalid
```
```
In drivers/md/dm-kcopyd.c (ffffffe0006f9256)
Location: include/linux/blkdev.h:1433
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In drivers/md/dm-table.c (ffffffff81851878)
Location: include/linux/blkdev.h:1433
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_area_is_invalid
```
```
In drivers/md/dm-kcopyd.c (ffffffff81859aa4)
Location: include/linux/blkdev.h:1433
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In drivers/md/dm-table.c (ffffffff81818e88)
Location: include/linux/blkdev.h:1433
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_area_is_invalid
```
```
In drivers/md/dm-kcopyd.c (ffffffff818210b4)
Location: include/linux/blkdev.h:1433
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In drivers/md/dm-table.c (ffffffff818a0ea8)
Location: include/linux/blkdev.h:1433
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_area_is_invalid
```
```
In drivers/md/dm-kcopyd.c (ffffffff818a90d4)
Location: include/linux/blkdev.h:1433
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
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
In drivers/md/dm-table.c (ffffffff818bd0e8)
Location: include/linux/blkdev.h:1433
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_area_is_invalid
```
```
In drivers/md/dm-kcopyd.c (ffffffff818c54e4)
Location: include/linux/blkdev.h:1433
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
</details>
</li>
</ul>

## Differences
