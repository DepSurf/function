# Function: <code>add_disk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void add_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff813cafb0)
Location: block/genhd.c:583
Inline: False
Direct callers:
  - drivers/block/brd.c:brd_init
  - drivers/block/brd.c:brd_probe
  - drivers/block/loop.c:loop_add
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/scsi/sd.c:sd_probe_async
  - drivers/scsi/sr.c:sr_probe
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff813cafb0-ffffffff813cb440: add_disk (STB_GLOBAL)
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
In drivers/block/brd.c (ffffffff81fda1ca)
Location: include/linux/genhd.h:417
Inline: True
Inline callers:
  - drivers/block/brd.c:brd_init
  - drivers/block/brd.c:brd_probe
```
```
In drivers/block/loop.c (ffffffff815c4fb9)
Location: include/linux/genhd.h:417
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_add
```
```
In drivers/md/md.c (ffffffff816f56d6)
Location: include/linux/genhd.h:417
Inline: True
Inline callers:
  - drivers/md/md.c:md_alloc
```
```
In drivers/md/dm.c (ffffffff81703e6d)
Location: include/linux/genhd.h:417
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
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
In drivers/block/loop.c (ffffffff815f36e9)
Location: include/linux/genhd.h:408
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_add
```
```
In drivers/md/md.c (ffffffff81726e06)
Location: include/linux/genhd.h:408
Inline: True
Inline callers:
  - drivers/md/md.c:md_alloc
```
```
In drivers/md/dm.c (ffffffff81735d32)
Location: include/linux/genhd.h:408
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
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
In drivers/lightnvm/core.c (ffffffff815d8d5f)
Location: include/linux/genhd.h:402
Inline: True
```
```
In drivers/block/loop.c (ffffffff81607a5e)
Location: include/linux/genhd.h:402
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_add
```
```
In drivers/md/md.c (ffffffff8173f5bf)
Location: include/linux/genhd.h:402
Inline: True
Inline callers:
  - drivers/md/md.c:md_alloc
```
```
In drivers/md/dm.c (ffffffff8174f18c)
Location: include/linux/genhd.h:402
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
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
In drivers/lightnvm/core.c (ffffffff8163faf9)
Location: include/linux/genhd.h:394
Inline: True
```
```
In drivers/block/loop.c (ffffffff81670110)
Location: include/linux/genhd.h:394
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_add
```
```
In drivers/md/md.c (ffffffff817b15d4)
Location: include/linux/genhd.h:394
Inline: True
Inline callers:
  - drivers/md/md.c:md_alloc
```
```
In drivers/md/dm.c (ffffffff817c13ad)
Location: include/linux/genhd.h:394
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
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
In drivers/lightnvm/core.c (ffffffff8167b2a6)
Location: include/linux/genhd.h:397
Inline: True
```
```
In drivers/block/loop.c (ffffffff816abbe4)
Location: include/linux/genhd.h:397
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_add
```
```
In drivers/md/md.c (ffffffff817f95fc)
Location: include/linux/genhd.h:397
Inline: True
Inline callers:
  - drivers/md/md.c:md_alloc
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
In drivers/lightnvm/core.c (ffffffff8169ac20)
Location: include/linux/genhd.h:420
Inline: True
```
```
In drivers/block/loop.c (ffffffff816cc97e)
Location: include/linux/genhd.h:420
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_add
```
```
In drivers/md/md.c (ffffffff818255d9)
Location: include/linux/genhd.h:420
Inline: True
Inline callers:
  - drivers/md/md.c:md_alloc
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
In drivers/lightnvm/core.c (ffffffff816d33f1)
Location: include/linux/genhd.h:427
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/block/loop.c (ffffffff81707e4c)
Location: include/linux/genhd.h:427
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_add
```
```
In drivers/md/md.c (ffffffff81867a3f)
Location: include/linux/genhd.h:427
Inline: True
Inline callers:
  - drivers/md/md.c:md_alloc
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
In drivers/lightnvm/core.c (ffffffff816f72d2)
Location: include/linux/genhd.h:427
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/block/loop.c (ffffffff8172c09c)
Location: include/linux/genhd.h:427
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_add
```
```
In drivers/md/md.c (ffffffff818997cf)
Location: include/linux/genhd.h:427
Inline: True
Inline callers:
  - drivers/md/md.c:md_alloc
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
In drivers/lightnvm/core.c (ffffffff817b010b)
Location: include/linux/genhd.h:294
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/block/loop.c (ffffffff817e7a5c)
Location: include/linux/genhd.h:294
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_add
```
```
In drivers/md/md.c (ffffffff81968e40)
Location: include/linux/genhd.h:294
Inline: True
Inline callers:
  - drivers/md/md.c:md_alloc
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
In drivers/lightnvm/core.c (ffffffff817c4cc1)
Location: include/linux/genhd.h:239
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/block/loop.c (ffffffff817fc93d)
Location: include/linux/genhd.h:239
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_add
```
```
In drivers/md/md.c (ffffffff8196f919)
Location: include/linux/genhd.h:239
Inline: True
Inline callers:
  - drivers/md/md.c:md_alloc
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
In drivers/lightnvm/core.c (ffffffff817a7b1f)
Location: include/linux/genhd.h:210
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/block/loop.c (ffffffff817e150e)
Location: include/linux/genhd.h:210
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_add
```
```
In drivers/md/md.c (ffffffff81952c0c)
Location: include/linux/genhd.h:210
Inline: True
Inline callers:
  - drivers/md/md.c:md_alloc
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
In drivers/block/loop.c (ffffffff8186d3e6)
Location: include/linux/genhd.h:210
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_add
```
```
In drivers/md/md.c (ffffffff819f8189)
Location: include/linux/genhd.h:210
Inline: True
Inline callers:
  - drivers/md/md.c:md_alloc
```
```
In drivers/md/dm.c (ffffffff81a0b53c)
Location: include/linux/genhd.h:210
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_setup_md_queue
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
In drivers/block/loop.c (ffffffff819b62b1)
Location: include/linux/blkdev.h:761
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_add
```
```
In drivers/md/md.c (ffffffff81b5e04a)
Location: include/linux/blkdev.h:761
Inline: True
Inline callers:
  - drivers/md/md.c:md_alloc
```
```
In drivers/md/dm.c (ffffffff81b73968)
Location: include/linux/blkdev.h:761
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_setup_md_queue
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
In drivers/block/loop.c (ffffffff81b2b454)
Location: include/linux/blkdev.h:749
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_add
```
```
In drivers/md/md.c (ffffffff81cfdfb9)
Location: include/linux/blkdev.h:749
Inline: True
Inline callers:
  - drivers/md/md.c:md_alloc
```
```
In drivers/md/dm.c (ffffffff81d105e6)
Location: include/linux/blkdev.h:749
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_setup_md_queue
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
In drivers/block/loop.c (ffffffff81b7b744)
Location: include/linux/blkdev.h:733
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_add
```
```
In drivers/md/md.c (ffffffff81d6511a)
Location: include/linux/blkdev.h:733
Inline: True
Inline callers:
  - drivers/md/md.c:md_alloc
```
```
In drivers/md/dm.c (ffffffff81d79a1a)
Location: include/linux/blkdev.h:733
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_setup_md_queue
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
In drivers/block/loop.c (ffffffff81bcf744)
Location: include/linux/blkdev.h:710
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_add
```
```
In drivers/md/md.c (ffffffff81e1be87)
Location: include/linux/blkdev.h:710
Inline: True
Inline callers:
  - drivers/md/md.c:md_alloc
```
```
In drivers/md/dm.c (ffffffff81e30bba)
Location: include/linux/blkdev.h:710
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_setup_md_queue
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
In drivers/lightnvm/core.c (ffff8000108e11ac)
Location: include/linux/genhd.h:427
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/block/loop.c (ffff800010921b00)
Location: include/linux/genhd.h:427
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_add
```
```
In drivers/md/md.c (ffff800010aeb6e4)
Location: include/linux/genhd.h:427
Inline: True
Inline callers:
  - drivers/md/md.c:md_alloc
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
In drivers/lightnvm/core.c (c09cfc98)
Location: include/linux/genhd.h:427
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/block/loop.c (c0a07354)
Location: include/linux/genhd.h:427
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_add
```
```
In drivers/md/md.c (c0bcbc20)
Location: include/linux/genhd.h:427
Inline: True
Inline callers:
  - drivers/md/md.c:md_alloc
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
In drivers/lightnvm/core.c (c000000000974f84)
Location: include/linux/genhd.h:427
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/block/loop.c (c0000000009c73e0)
Location: include/linux/genhd.h:427
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_add
```
```
In drivers/md/md.c (c000000000bd896c)
Location: include/linux/genhd.h:427
Inline: True
Inline callers:
  - drivers/md/md.c:md_alloc
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
In drivers/lightnvm/core.c (ffffffe000576952)
Location: include/linux/genhd.h:427
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/block/loop.c (ffffffe0005a0d74)
Location: include/linux/genhd.h:427
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_add
```
```
In drivers/md/md.c (ffffffe0006e2144)
Location: include/linux/genhd.h:427
Inline: True
Inline callers:
  - drivers/md/md.c:md_alloc
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
In drivers/lightnvm/core.c (ffffffff816bcac2)
Location: include/linux/genhd.h:427
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/block/loop.c (ffffffff816f1e7c)
Location: include/linux/genhd.h:427
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_add
```
```
In drivers/md/md.c (ffffffff8183f64f)
Location: include/linux/genhd.h:427
Inline: True
Inline callers:
  - drivers/md/md.c:md_alloc
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
In drivers/block/loop.c (ffffffff816cbf7c)
Location: include/linux/genhd.h:427
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_add
```
```
In drivers/md/md.c (ffffffff81806caf)
Location: include/linux/genhd.h:427
Inline: True
Inline callers:
  - drivers/md/md.c:md_alloc
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
In drivers/lightnvm/core.c (ffffffff816eaf92)
Location: include/linux/genhd.h:427
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/block/loop.c (ffffffff8171f55c)
Location: include/linux/genhd.h:427
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_add
```
```
In drivers/md/md.c (ffffffff8188ec7f)
Location: include/linux/genhd.h:427
Inline: True
Inline callers:
  - drivers/md/md.c:md_alloc
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
In drivers/lightnvm/core.c (ffffffff817057d2)
Location: include/linux/genhd.h:427
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/block/loop.c (ffffffff8173a98c)
Location: include/linux/genhd.h:427
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_add
```
```
In drivers/md/md.c (ffffffff818a99df)
Location: include/linux/genhd.h:427
Inline: True
Inline callers:
  - drivers/md/md.c:md_alloc
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
