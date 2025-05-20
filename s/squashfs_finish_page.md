# Function: <code>squashfs_finish_page</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/squashfs/block.c (ffffffff8132103d)
Location: fs/squashfs/page_actor.h:76
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff81325f8a)
Location: fs/squashfs/page_actor.h:76
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff81326290)
Location: fs/squashfs/page_actor.h:76
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff81326546)
Location: fs/squashfs/page_actor.h:76
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff8132682b)
Location: fs/squashfs/page_actor.h:76
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
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
In fs/squashfs/block.c (ffffffff81336eed)
Location: fs/squashfs/page_actor.h:76
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff8133bd3a)
Location: fs/squashfs/page_actor.h:76
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff8133c040)
Location: fs/squashfs/page_actor.h:76
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff8133c2f6)
Location: fs/squashfs/page_actor.h:76
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff8133c5db)
Location: fs/squashfs/page_actor.h:76
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
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
In fs/squashfs/block.c (ffffffff8134bbda)
Location: fs/squashfs/page_actor.h:76
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff8135083e)
Location: fs/squashfs/page_actor.h:76
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff81350b35)
Location: fs/squashfs/page_actor.h:76
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff81350dff)
Location: fs/squashfs/page_actor.h:76
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff813510d7)
Location: fs/squashfs/page_actor.h:76
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
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
In fs/squashfs/block.c (ffffffff81370236)
Location: fs/squashfs/page_actor.h:76
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff81374fe3)
Location: fs/squashfs/page_actor.h:76
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff813752f4)
Location: fs/squashfs/page_actor.h:76
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff813755c9)
Location: fs/squashfs/page_actor.h:76
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff813758b1)
Location: fs/squashfs/page_actor.h:76
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff81375b8c)
Location: fs/squashfs/page_actor.h:76
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
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
In fs/squashfs/block.c (ffffffff8139ea18)
Location: fs/squashfs/page_actor.h:76
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff813a39d0)
Location: fs/squashfs/page_actor.h:76
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff813a3ce1)
Location: fs/squashfs/page_actor.h:76
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff813a3fd4)
Location: fs/squashfs/page_actor.h:76
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff813a42cf)
Location: fs/squashfs/page_actor.h:76
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff813a459a)
Location: fs/squashfs/page_actor.h:76
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
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
In fs/squashfs/block.c (ffffffff813b7796)
Location: fs/squashfs/page_actor.h:76
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff813bc7d0)
Location: fs/squashfs/page_actor.h:76
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff813bcae1)
Location: fs/squashfs/page_actor.h:76
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff813bcdd4)
Location: fs/squashfs/page_actor.h:76
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff813bd0cf)
Location: fs/squashfs/page_actor.h:76
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff813bd39a)
Location: fs/squashfs/page_actor.h:76
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
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
In fs/squashfs/block.c (ffffffff813e1f45)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff813e7075)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff813e7385)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff813e7680)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff813e7988)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff813e7c59)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
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
In fs/squashfs/block.c (ffffffff813fbf75)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff814010f5)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff81401405)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff81401700)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff81401a08)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff81401cd9)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
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
In fs/squashfs/block.c (ffffffff81449677)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/block.c:copy_bio_to_actor
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff8144eaf1)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff8144eea4)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff8144f2a6)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff8144f5f3)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff8144f8e6)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
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
In fs/squashfs/block.c (ffffffff81465de7)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/block.c:copy_bio_to_actor
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff8146b0e1)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff8146b464)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff8146b846)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff8146bb73)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff8146be46)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
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
In fs/squashfs/block.c (ffffffff8146b590)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/block.c:copy_bio_to_actor
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff814707a1)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff81470b26)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff81470ef6)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff81471202)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff814714d6)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
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
In fs/squashfs/block.c (ffffffff814c1de1)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/block.c:copy_bio_to_actor
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff814c7211)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff814c7596)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff814c7966)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff814c7c92)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff814c7f66)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
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
In fs/squashfs/block.c (ffffffff8154c80f)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/block.c:copy_bio_to_actor
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff815525c2)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff81552979)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff81552ced)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff815530ed)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff81553355)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
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
In fs/squashfs/block.c (ffffffff815ec66f)
Location: fs/squashfs/page_actor.h:49
Inline: True
Inline callers:
  - fs/squashfs/block.c:copy_bio_to_actor
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff815f3b2d)
Location: fs/squashfs/page_actor.h:49
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff815f3f73)
Location: fs/squashfs/page_actor.h:49
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff815f4305)
Location: fs/squashfs/page_actor.h:49
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff815f4795)
Location: fs/squashfs/page_actor.h:49
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff815f4a74)
Location: fs/squashfs/page_actor.h:49
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
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
In fs/squashfs/block.c (ffffffff816245cf)
Location: fs/squashfs/page_actor.h:49
Inline: True
Inline callers:
  - fs/squashfs/block.c:copy_bio_to_actor
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff8162bc1d)
Location: fs/squashfs/page_actor.h:49
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff8162c063)
Location: fs/squashfs/page_actor.h:49
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff8162c3f6)
Location: fs/squashfs/page_actor.h:49
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff8162c865)
Location: fs/squashfs/page_actor.h:49
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff8162cb0c)
Location: fs/squashfs/page_actor.h:49
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
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
In fs/squashfs/block.c (ffffffff8165d65f)
Location: fs/squashfs/page_actor.h:49
Inline: True
Inline callers:
  - fs/squashfs/block.c:copy_bio_to_actor
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff81664fed)
Location: fs/squashfs/page_actor.h:49
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff81665463)
Location: fs/squashfs/page_actor.h:49
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff81665826)
Location: fs/squashfs/page_actor.h:49
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff81665cf5)
Location: fs/squashfs/page_actor.h:49
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff81665fcc)
Location: fs/squashfs/page_actor.h:49
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
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
In fs/squashfs/block.c (ffff8000104d9c0c)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffff8000104df3b4)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffff8000104df64c)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffff8000104df908)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffff8000104dfcb4)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffff8000104dff84)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
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
In fs/squashfs/block.c (c069b4d4)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (c06a0d28)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (c06a0fb4)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (c06a1240)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (c06a15b0)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (c06a1898)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
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
In fs/squashfs/block.c (c0000000006145f0)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (c00000000061b4f4)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (c00000000061b8c0)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (c00000000061bc90)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (c00000000061c15c)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (c00000000061c580)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
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
In fs/squashfs/block.c (ffffffe00034ed3e)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffffffe000353950)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffe000353ba6)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffe000353d44)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffe000354084)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffe00035427c)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
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
In fs/squashfs/block.c (ffffffff813f4555)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff813f96d5)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff813f99e5)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff813f9ce0)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff813f9fe8)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff813fa2b9)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
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
In fs/squashfs/block.c (ffffffff813e4fd5)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff813ea155)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff813ea465)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff813ea760)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff813eaa68)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff813ead39)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
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
In fs/squashfs/block.c (ffffffff813f18d5)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff813f6a55)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff813f6d65)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff813f7060)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff813f7368)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff813f7639)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
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
In fs/squashfs/block.c (ffffffff814074d9)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff8140c6e5)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff8140c9f5)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff8140ccf0)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff8140cff8)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff8140d2c9)
Location: fs/squashfs/page_actor.h:74
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
</details>
</li>
</ul>

## Differences
