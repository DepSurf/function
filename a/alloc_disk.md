# Function: <code>alloc_disk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct gendisk *alloc_disk(int minors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff813cb6a0)
Location: block/genhd.c:1255
Inline: False
Direct callers:
  - drivers/block/brd.c:brd_alloc
  - drivers/block/loop.c:loop_add
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sg.c:sg_add_device
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff813cb6a0-ffffffff813cb6b5: alloc_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct gendisk *alloc_disk(int minors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8140f960)
Location: block/genhd.c:1284
Inline: False
Direct callers:
  - drivers/block/brd.c:brd_alloc
  - drivers/block/loop.c:loop_add
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sg.c:sg_add_device
  - drivers/md/md.c:md_alloc
```
**Symbols:**

```
ffffffff8140f960-ffffffff8140f975: alloc_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct gendisk *alloc_disk(int minors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8142acf0)
Location: block/genhd.c:1284
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sg.c:sg_add_device
  - drivers/md/md.c:md_alloc
```
**Symbols:**

```
ffffffff8142acf0-ffffffff8142ad05: alloc_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct gendisk *alloc_disk(int minors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81438f00)
Location: block/genhd.c:1307
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sg.c:sg_add_device
  - drivers/md/md.c:md_alloc
```
**Symbols:**

```
ffffffff81438f00-ffffffff81438f15: alloc_disk (STB_GLOBAL)
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
</ul>
