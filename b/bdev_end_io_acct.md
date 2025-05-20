# Function: <code>bdev_end_io_acct</code>

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
void bdev_end_io_acct(struct block_device *bdev, unsigned int op, long unsigned int start_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81679bc0)
Location: block/blk-core.c:1041
Inline: False
Direct callers:
  - block/blk-core.c:bio_end_io_acct_remapped
  - drivers/md/dm.c:dm_io_acct
```
**Symbols:**

```
ffffffff81679bc0-ffffffff81679cc8: bdev_end_io_acct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bdev_end_io_acct(struct block_device *bdev, enum req_op op, long unsigned int start_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81736020)
Location: block/blk-core.c:979
Inline: False
Direct callers:
  - block/blk-core.c:bio_end_io_acct_remapped
  - drivers/md/dm.c:dm_io_acct
```
**Symbols:**

```
ffffffff81736020-ffffffff81736128: bdev_end_io_acct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bdev_end_io_acct(struct block_device *bdev, enum req_op op, unsigned int sectors, long unsigned int start_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81772540)
Location: block/blk-core.c:976
Inline: False
Direct callers:
  - block/blk-core.c:bio_end_io_acct_remapped
  - drivers/md/dm.c:dm_io_acct
```
**Symbols:**

```
ffffffff81772540-ffffffff817726cb: bdev_end_io_acct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bdev_end_io_acct(struct block_device *bdev, enum req_op op, unsigned int sectors, long unsigned int start_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff817b48e0)
Location: block/blk-core.c:1011
Inline: False
Direct callers:
  - block/blk-core.c:bio_end_io_acct_remapped
  - drivers/md/dm.c:dm_io_acct
```
**Symbols:**

```
ffffffff817b48e0-ffffffff817b4a6b: bdev_end_io_acct (STB_GLOBAL)
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
<b>Param added. </b>
<code>unsigned int sectors</code>
</li>
<li>
<b>Param reordered. </b>
<code>bdev, op, start_time</code> ➡️ <code>bdev, op, sectors, start_time</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
