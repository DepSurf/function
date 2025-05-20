# Function: <code>__disk_get_part</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct hd_struct *__disk_get_part(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814639bc)
Location: block/genhd.c:85
Inline: True
Inline callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:bdget_disk
Direct callers:
  - fs/buffer.c:guard_bio_eod
  - block/blk-core.c:generic_make_request_checks
```
**Symbols:**

```
ffffffff81464680-ffffffff814646a7: __disk_get_part (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct hd_struct *__disk_get_part(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814973c0)
Location: block/genhd.c:97
Inline: True
Inline callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:bdget_disk
Direct callers:
  - fs/buffer.c:guard_bio_eod
  - block/blk-core.c:generic_make_request_checks
```
**Symbols:**

```
ffffffff81497fd0-ffffffff81497ff7: __disk_get_part (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct hd_struct *__disk_get_part(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814b12e0)
Location: block/genhd.c:110
Inline: True
Inline callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:bdget_disk
Direct callers:
  - fs/buffer.c:guard_bio_eod
  - block/blk-core.c:generic_make_request_checks
```
**Symbols:**

```
ffffffff814b20f0-ffffffff814b2117: __disk_get_part (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct hd_struct *__disk_get_part(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814decdb)
Location: block/genhd.c:111
Inline: True
Inline callers:
  - block/genhd.c:disk_get_part
Direct callers:
  - fs/buffer.c:guard_bio_eod
  - block/blk-core.c:generic_make_request_checks
```
**Symbols:**

```
ffffffff814e0540-ffffffff814e0567: __disk_get_part (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct hd_struct *__disk_get_part(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814f811b)
Location: block/genhd.c:111
Inline: True
Inline callers:
  - block/genhd.c:disk_get_part
Direct callers:
  - fs/buffer.c:guard_bio_eod
  - block/blk-core.c:generic_make_request_checks
```
**Symbols:**

```
ffffffff814f9970-ffffffff814f9997: __disk_get_part (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct hd_struct *__disk_get_part(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8155b17b)
Location: block/genhd.c:148
Inline: True
Inline callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:bdget_disk
Direct callers:
  - block/bio.c:guard_bio_eod
  - block/blk-core.c:generic_make_request_checks
```
**Symbols:**

```
ffffffff8155a7d0-ffffffff8155a7f7: __disk_get_part (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct block_device *__disk_get_part(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff815773b1)
Location: block/genhd.c:165
Inline: True
Inline callers:
  - block/genhd.c:blk_lookup_devt
Direct callers:
  - block/bio.c:guard_bio_eod
  - block/blk-core.c:submit_bio_checks
```
**Symbols:**

```
ffffffff81576be0-ffffffff81576c07: __disk_get_part (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct hd_struct *__disk_get_part(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffff8000105f936c)
Location: block/genhd.c:111
Inline: True
Inline callers:
  - block/genhd.c:disk_get_part
Direct callers:
  - fs/buffer.c:guard_bio_eod
  - block/blk-core.c:generic_make_request_checks
```
**Symbols:**

```
ffff8000105fb370-ffff8000105fb3c4: __disk_get_part (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct hd_struct *__disk_get_part(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (c07a4600)
Location: block/genhd.c:111
Inline: True
Inline callers:
  - block/genhd.c:disk_get_part
Direct callers:
  - fs/buffer.c:guard_bio_eod
  - block/blk-core.c:generic_make_request_checks
```
**Symbols:**

```
c07a6440-c07a6480: __disk_get_part (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct hd_struct *__disk_get_part(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (c000000000791978)
Location: block/genhd.c:111
Inline: True
Inline callers:
  - block/genhd.c:disk_get_part
Direct callers:
  - fs/buffer.c:guard_bio_eod
  - block/blk-core.c:generic_make_request_checks
```
**Symbols:**

```
c000000000794510-c000000000794548: __disk_get_part (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct hd_struct *__disk_get_part(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffe000435b4a)
Location: block/genhd.c:111
Inline: True
Inline callers:
  - block/genhd.c:disk_get_part
Direct callers:
  - fs/buffer.c:guard_bio_eod
  - block/blk-core.c:generic_make_request_checks
```
**Symbols:**

```
ffffffe000437546-ffffffe000437590: __disk_get_part (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct hd_struct *__disk_get_part(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814f06fb)
Location: block/genhd.c:111
Inline: True
Inline callers:
  - block/genhd.c:disk_get_part
Direct callers:
  - fs/buffer.c:guard_bio_eod
  - block/blk-core.c:generic_make_request_checks
```
**Symbols:**

```
ffffffff814f1f50-ffffffff814f1f77: __disk_get_part (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct hd_struct *__disk_get_part(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814e0c3b)
Location: block/genhd.c:111
Inline: True
Inline callers:
  - block/genhd.c:disk_get_part
Direct callers:
  - fs/buffer.c:guard_bio_eod
  - block/blk-core.c:generic_make_request_checks
```
**Symbols:**

```
ffffffff814e2480-ffffffff814e24a7: __disk_get_part (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct hd_struct *__disk_get_part(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814ec78b)
Location: block/genhd.c:111
Inline: True
Inline callers:
  - block/genhd.c:disk_get_part
Direct callers:
  - fs/buffer.c:guard_bio_eod
  - block/blk-core.c:generic_make_request_checks
```
**Symbols:**

```
ffffffff814edfe0-ffffffff814ee007: __disk_get_part (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct hd_struct *__disk_get_part(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff815057d7)
Location: block/genhd.c:111
Inline: True
Inline callers:
  - block/genhd.c:disk_get_part
Direct callers:
  - fs/buffer.c:guard_bio_eod
  - block/blk-core.c:generic_make_request_checks
```
**Symbols:**

```
ffffffff81507060-ffffffff81507087: __disk_get_part (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>struct hd_struct *</code> ➡️ <code>struct block_device *</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
