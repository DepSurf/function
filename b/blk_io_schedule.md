# Function: <code>blk_io_schedule</code>

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
void blk_io_schedule();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81542db0)
Location: block/blk-core.c:1883
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:dio_await_one
  - fs/iomap/direct-io.c:iomap_dio_rw
```
**Symbols:**

```
ffffffff81542db0-ffffffff81542ddb: blk_io_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_io_schedule();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8155f6c0)
Location: block/blk-core.c:1778
Inline: False
Direct callers:
  - mm/page_io.c:swap_readpage
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:dio_await_one
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
**Symbols:**

```
ffffffff8155f6c0-ffffffff8155f6eb: blk_io_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_io_schedule();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81567e60)
Location: block/blk-core.c:1770
Inline: False
Direct callers:
  - mm/page_io.c:swap_readpage
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
**Symbols:**

```
ffffffff81567e60-ffffffff81567e8b: blk_io_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_io_schedule();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815cc4b0)
Location: block/blk-core.c:1756
Inline: False
Direct callers:
  - mm/page_io.c:swap_readpage
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - block/fops.c:__blkdev_direct_IO
  - block/fops.c:__blkdev_direct_IO_simple
```
**Symbols:**

```
ffffffff815cc4b0-ffffffff815cc4db: blk_io_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_io_schedule();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81678280)
Location: block/blk-core.c:1236
Inline: False
Direct callers:
  - mm/page_io.c:swap_readpage
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - block/fops.c:__blkdev_direct_IO
```
**Symbols:**

```
ffffffff81678280-ffffffff816782bb: blk_io_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_io_schedule();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81733960)
Location: block/blk-core.c:1174
Inline: False
Direct callers:
  - mm/page_io.c:swap_readpage
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - block/fops.c:__blkdev_direct_IO
```
**Symbols:**

```
ffffffff81733960-ffffffff8173399b: blk_io_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_io_schedule();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8176fd80)
Location: block/blk-core.c:1171
Inline: False
Direct callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
**Symbols:**

```
ffffffff8176fd80-ffffffff8176fdbb: blk_io_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_io_schedule();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff817b1ff0)
Location: block/blk-core.c:1206
Inline: False
Direct callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
**Symbols:**

```
ffffffff817b1ff0-ffffffff817b202b: blk_io_schedule (STB_GLOBAL)
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
