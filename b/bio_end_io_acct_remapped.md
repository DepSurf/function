# Function: <code>bio_end_io_acct_remapped</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bio_end_io_acct_remapped(struct bio *bio, long unsigned int start_time, struct block_device *orig_bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81567d80)
Location: block/blk-core.c:1361
Inline: False
Direct callers:
  - drivers/md/dm.c:dec_pending
```
**Symbols:**

```
ffffffff81567d80-ffffffff81567da1: bio_end_io_acct_remapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bio_end_io_acct_remapped(struct bio *bio, long unsigned int start_time, struct block_device *orig_bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815cc3d0)
Location: block/blk-core.c:1351
Inline: False
Direct callers:
  - drivers/md/md.c:md_end_io_acct
  - drivers/md/dm.c:dm_io_dec_pending
```
**Symbols:**

```
ffffffff815cc3d0-ffffffff815cc3f1: bio_end_io_acct_remapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bio_end_io_acct_remapped(struct bio *bio, long unsigned int start_time, struct block_device *orig_bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81679cd0)
Location: block/blk-core.c:1056
Inline: False
Direct callers:
  - drivers/md/md.c:md_end_io_acct
```
**Symbols:**

```
ffffffff81679cd0-ffffffff81679cfb: bio_end_io_acct_remapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bio_end_io_acct_remapped(struct bio *bio, long unsigned int start_time, struct block_device *orig_bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81736140)
Location: block/blk-core.c:994
Inline: False
Direct callers:
  - drivers/md/md.c:md_end_io_acct
```
**Symbols:**

```
ffffffff81736140-ffffffff8173616b: bio_end_io_acct_remapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bio_end_io_acct_remapped(struct bio *bio, long unsigned int start_time, struct block_device *orig_bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff817726e0)
Location: block/blk-core.c:993
Inline: False
Direct callers:
  - drivers/md/md.c:md_end_io_acct
```
**Symbols:**

```
ffffffff817726e0-ffffffff81772711: bio_end_io_acct_remapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bio_end_io_acct_remapped(struct bio *bio, long unsigned int start_time, struct block_device *orig_bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff817b4a80)
Location: block/blk-core.c:1028
Inline: False
Direct callers:
  - drivers/md/md.c:md_end_clone_io
```
**Symbols:**

```
ffffffff817b4a80-ffffffff817b4ab1: bio_end_io_acct_remapped (STB_GLOBAL)
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
