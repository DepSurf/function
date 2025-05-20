# Function: <code>bdev_stable_writes</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81382609)
Location: include/linux/blkdev.h:1305
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In fs/super.c (ffffffff813f4d88)
Location: include/linux/blkdev.h:1305
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
```
In drivers/md/dm-table.c (ffffffff81b74885)
Location: include/linux/blkdev.h:1305
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_requires_stable_pages
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
In mm/swapfile.c (ffffffff813fc574)
Location: include/linux/blkdev.h:1253
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In fs/super.c (ffffffff8147ded8)
Location: include/linux/blkdev.h:1253
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
```
In drivers/md/dm-table.c (ffffffff81d117d5)
Location: include/linux/blkdev.h:1253
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_requires_stable_pages
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
In mm/swapfile.c (ffffffff8142f883)
Location: include/linux/blkdev.h:1240
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In fs/super.c (ffffffff814b2c65)
Location: include/linux/blkdev.h:1240
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
```
In drivers/md/dm-table.c (ffffffff81d7ac35)
Location: include/linux/blkdev.h:1240
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_requires_stable_pages
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
In mm/swapfile.c (ffffffff81469452)
Location: include/linux/blkdev.h:1225
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In fs/super.c (ffffffff814e410e)
Location: include/linux/blkdev.h:1225
Inline: True
Inline callers:
  - fs/super.c:setup_bdev_super
```
```
In block/bdev.c (ffffffff817a86f5)
Location: include/linux/blkdev.h:1225
Inline: True
Inline callers:
  - block/bdev.c:bdev_add
```
```
In drivers/md/dm-table.c (ffffffff81e31d45)
Location: include/linux/blkdev.h:1225
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_requires_stable_pages
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
