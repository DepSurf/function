# Function: <code>bdev_start_io_acct</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int bdev_start_io_acct(struct block_device *bdev, unsigned int sectors, unsigned int op, long unsigned int start_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81679a30)
Location: block/blk-core.c:999
Inline: False
Direct callers:
  - block/blk-core.c:bio_start_io_acct
  - block/blk-core.c:bio_start_io_acct_time
  - drivers/md/dm.c:dm_io_acct
```
**Symbols:**

```
ffffffff81679a30-ffffffff81679b47: bdev_start_io_acct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int bdev_start_io_acct(struct block_device *bdev, unsigned int sectors, enum req_op op, long unsigned int start_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81735ea0)
Location: block/blk-core.c:949
Inline: False
Direct callers:
  - block/blk-core.c:bio_start_io_acct
  - drivers/md/dm.c:dm_io_acct
```
**Symbols:**

```
ffffffff81735ea0-ffffffff81735fb7: bdev_start_io_acct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long unsigned int bdev_start_io_acct(struct block_device *bdev, enum req_op op, long unsigned int start_time);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8177274f)
Location: block/blk-core.c:952
Inline: True
Inline callers:
  - block/blk-core.c:bio_start_io_acct
Direct callers:
  - drivers/md/dm.c:dm_io_acct
```
**Symbols:**

```
ffffffff81772480-ffffffff81772528: bdev_start_io_acct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int bdev_start_io_acct(struct block_device *bdev, enum req_op op, long unsigned int start_time);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff817b4aef)
Location: block/blk-core.c:987
Inline: True
Inline callers:
  - block/blk-core.c:bio_start_io_acct
Direct callers:
  - drivers/md/dm.c:dm_io_acct
```
**Symbols:**

```
ffffffff817b4820-ffffffff817b48c8: bdev_start_io_acct (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned int op</code> ➡️ <code>enum req_op op</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>unsigned int sectors</code>
</li>
<li>
<b>Param reordered. </b>
<code>bdev, sectors, op, start_time</code> ➡️ <code>bdev, op, start_time</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
