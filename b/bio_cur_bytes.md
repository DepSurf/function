# Function: <code>bio_cur_bytes</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813b6816)
Location: include/linux/bio.h:134
Inline: True
Inline callers:
  - block/blk-core.c:blk_dump_rq_flags
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_end_request_cur
  - block/blk-core.c:__blk_end_request_cur
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fee72)
Location: include/linux/bio.h:107
Inline: True
Inline callers:
  - block/blk-core.c:__blk_end_request_cur
  - block/blk-core.c:blk_end_request_cur
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_dump_rq_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814188a2)
Location: include/linux/bio.h:102
Inline: True
Inline callers:
  - block/blk-core.c:__blk_end_request_cur
  - block/blk-core.c:blk_end_request_cur
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_dump_rq_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81425e94)
Location: include/linux/bio.h:102
Inline: True
Inline callers:
  - block/blk-core.c:__blk_end_request_cur
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_dump_rq_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81451004)
Location: include/linux/bio.h:110
Inline: True
Inline callers:
  - block/blk-core.c:__blk_end_request_cur
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_dump_rq_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
unsigned int bio_cur_bytes(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81484284)
Location: include/linux/bio.h:114
Inline: True
Inline callers:
  - block/blk-core.c:__blk_end_request_cur
  - block/blk-core.c:blk_update_request
Direct callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_dump_rq_flags
```
**Symbols:**

```
ffffffff814806e0-ffffffff81480715: bio_cur_bytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
unsigned int bio_cur_bytes(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8149f27b)
Location: include/linux/bio.h:110
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
Direct callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_dump_rq_flags
```
**Symbols:**

```
ffffffff8149d3d0-ffffffff8149d405: bio_cur_bytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
unsigned int bio_cur_bytes(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cd3f0)
Location: include/linux/bio.h:89
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
Direct callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_dump_rq_flags
```
**Symbols:**

```
ffffffff814cb4d0-ffffffff814cb51e: bio_cur_bytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
unsigned int bio_cur_bytes(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814e66f4)
Location: include/linux/bio.h:89
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
Direct callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_dump_rq_flags
```
**Symbols:**

```
ffffffff814e46c0-ffffffff814e470e: bio_cur_bytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int bio_cur_bytes(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81543924)
Location: include/linux/bio.h:89
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
Direct callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_dump_rq_flags
```
**Symbols:**

```
ffffffff81543010-ffffffff8154305e: bio_cur_bytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
unsigned int bio_cur_bytes(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81560803)
Location: include/linux/bio.h:87
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
Direct callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_dump_rq_flags
```
**Symbols:**

```
ffffffff8155f860-ffffffff8155f8ae: bio_cur_bytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
unsigned int bio_cur_bytes(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81568e69)
Location: include/linux/bio.h:90
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
Direct callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_dump_rq_flags
```
**Symbols:**

```
ffffffff81567fc0-ffffffff8156800e: bio_cur_bytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
unsigned int bio_cur_bytes(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815cd110)
Location: include/linux/bio.h:89
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
Direct callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_dump_rq_flags
```
**Symbols:**

```
ffffffff815cc6d0-ffffffff815cc71e: bio_cur_bytes (STB_LOCAL)
```
</details>
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
unsigned int bio_cur_bytes(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffff8000105e3e10)
Location: include/linux/bio.h:89
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
Direct callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_dump_rq_flags
```
**Symbols:**

```
ffff8000105e0b80-ffff8000105e0be4: bio_cur_bytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int bio_cur_bytes(struct bio *bio);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c0790fb8)
Location: include/linux/bio.h:89
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
Direct callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_dump_rq_flags
```
```
In drivers/mtd/mtd_blkdevs.c (c0a98730)
Location: include/linux/bio.h:89
Inline: True
Inline callers:
  - drivers/mtd/mtd_blkdevs.c:mtd_blktrans_work
  - drivers/mtd/mtd_blkdevs.c:mtd_blktrans_work
```
**Symbols:**

```
c078ee0c-c078ee84: bio_cur_bytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
unsigned int bio_cur_bytes(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c000000000777ab0)
Location: include/linux/bio.h:89
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
Direct callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_dump_rq_flags
```
**Symbols:**

```
c000000000775010-c000000000775098: bio_cur_bytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
unsigned int bio_cur_bytes(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffe0004256b0)
Location: include/linux/bio.h:89
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
Direct callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_dump_rq_flags
```
**Symbols:**

```
ffffffe000423e2c-ffffffe000423e90: bio_cur_bytes (STB_LOCAL)
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
unsigned int bio_cur_bytes(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814decd4)
Location: include/linux/bio.h:89
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
Direct callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_dump_rq_flags
```
**Symbols:**

```
ffffffff814dcca0-ffffffff814dccee: bio_cur_bytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
unsigned int bio_cur_bytes(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cf674)
Location: include/linux/bio.h:89
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
Direct callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_dump_rq_flags
```
**Symbols:**

```
ffffffff814cd650-ffffffff814cd69e: bio_cur_bytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
unsigned int bio_cur_bytes(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814dad64)
Location: include/linux/bio.h:89
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
Direct callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_dump_rq_flags
```
**Symbols:**

```
ffffffff814d8d30-ffffffff814d8d7e: bio_cur_bytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
unsigned int bio_cur_bytes(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814f3af4)
Location: include/linux/bio.h:89
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
Direct callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_dump_rq_flags
```
**Symbols:**

```
ffffffff814f1940-ffffffff814f198e: bio_cur_bytes (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
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
