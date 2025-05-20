# Function: <code>set_capacity_and_notify</code>

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
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
bool set_capacity_and_notify(struct gendisk *disk, sector_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/genhd.c (0)
Location: block/genhd.c:60
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_configure
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:update_size
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_run
  - drivers/md/dm.c:__bind
```
**Symbols:**

```
ffffffff81bf2887-ffffffff81bf28d1: set_capacity_and_notify.cold (STB_LOCAL)
ffffffff815768d0-ffffffff81576981: set_capacity_and_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool set_capacity_and_notify(struct gendisk *disk, sector_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/genhd.c (0)
Location: block/genhd.c:57
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_configure
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:update_size
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_run
  - drivers/md/dm.c:__bind
```
**Symbols:**

```
ffffffff81be484d-ffffffff81be4897: set_capacity_and_notify.cold (STB_LOCAL)
ffffffff8157e7d0-ffffffff8157e880: set_capacity_and_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool set_capacity_and_notify(struct gendisk *disk, sector_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/genhd.c (0)
Location: block/genhd.c:69
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_configure
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:update_size
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_run
  - drivers/md/dm.c:__bind
```
**Symbols:**

```
ffffffff81cd88f1-ffffffff81cd8939: set_capacity_and_notify.cold (STB_LOCAL)
ffffffff815e4100-ffffffff815e41b9: set_capacity_and_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool set_capacity_and_notify(struct gendisk *disk, sector_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/genhd.c (0)
Location: block/genhd.c:73
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_configure
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:update_size
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:array_size_store
  - drivers/md/dm.c:__bind
```
**Symbols:**

```
ffffffff81e8c395-ffffffff81e8c3df: set_capacity_and_notify.cold (STB_LOCAL)
ffffffff81692ca0-ffffffff81692d62: set_capacity_and_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool set_capacity_and_notify(struct gendisk *disk, sector_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81751a00)
Location: block/genhd.c:73
Inline: False
Direct callers:
  - block/genhd.c:blk_mark_disk_dead
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_configure
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:update_size
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:array_size_store
```
**Symbols:**

```
ffffffff81751a00-ffffffff81751b00: set_capacity_and_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool set_capacity_and_notify(struct gendisk *disk, sector_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8178c320)
Location: block/genhd.c:69
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_configure
  - drivers/block/virtio_blk.c:virtblk_config_changed_work
  - drivers/block/virtio_blk.c:virtblk_update_capacity
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:update_size
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:array_size_store
```
**Symbols:**

```
ffffffff8178c320-ffffffff8178c3f1: set_capacity_and_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool set_capacity_and_notify(struct gendisk *disk, sector_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff817ceac0)
Location: block/genhd.c:69
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_configure
  - drivers/block/virtio_blk.c:virtblk_update_capacity
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:update_size
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:array_size_store
```
**Symbols:**

```
ffffffff817ceac0-ffffffff817ceb91: set_capacity_and_notify (STB_GLOBAL)
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
