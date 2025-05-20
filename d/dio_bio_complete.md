# Function: <code>dio_bio_complete</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int dio_bio_complete(struct dio *dio, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81249840)
Location: fs/direct-io.c:465
Inline: False
Direct callers:
  - fs/direct-io.c:dio_bio_end_aio
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
**Symbols:**

```
ffffffff81249840-ffffffff812498f8: dio_bio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dio_bio_complete(struct dio *dio, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff812724c0)
Location: fs/direct-io.c:474
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:dio_bio_end_aio
```
**Symbols:**

```
ffffffff812724c0-ffffffff812725c0: dio_bio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dio_bio_complete(struct dio *dio, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81285fe0)
Location: fs/direct-io.c:477
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:dio_bio_end_aio
```
**Symbols:**

```
ffffffff81285fe0-ffffffff812860e0: dio_bio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
blk_status_t dio_bio_complete(struct dio *dio, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81293640)
Location: fs/direct-io.c:478
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:dio_bio_end_aio
```
**Symbols:**

```
ffffffff81293640-ffffffff81293737: dio_bio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
blk_status_t dio_bio_complete(struct dio *dio, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff812b6510)
Location: fs/direct-io.c:517
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:dio_bio_end_aio
```
**Symbols:**

```
ffffffff812b6510-ffffffff812b663f: dio_bio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
blk_status_t dio_bio_complete(struct dio *dio, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff812de090)
Location: fs/direct-io.c:538
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:dio_bio_end_aio
```
**Symbols:**

```
ffffffff812de090-ffffffff812de1cc: dio_bio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
blk_status_t dio_bio_complete(struct dio *dio, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff812f3730)
Location: fs/direct-io.c:538
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:dio_bio_end_aio
```
**Symbols:**

```
ffffffff812f3730-ffffffff812f386e: dio_bio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
blk_status_t dio_bio_complete(struct dio *dio, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81315070)
Location: fs/direct-io.c:539
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:dio_bio_end_aio
```
**Symbols:**

```
ffffffff81315070-ffffffff81315102: dio_bio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
blk_status_t dio_bio_complete(struct dio *dio, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81327ef0)
Location: fs/direct-io.c:538
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:dio_bio_end_aio
```
**Symbols:**

```
ffffffff81327ef0-ffffffff81327f82: dio_bio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
blk_status_t dio_bio_complete(struct dio *dio, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81361c70)
Location: fs/direct-io.c:519
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:dio_bio_end_aio
```
**Symbols:**

```
ffffffff81361c70-ffffffff81361d02: dio_bio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
blk_status_t dio_bio_complete(struct dio *dio, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff8136ee20)
Location: fs/direct-io.c:500
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:dio_bio_end_aio
```
**Symbols:**

```
ffffffff8136ee20-ffffffff8136eeb2: dio_bio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
blk_status_t dio_bio_complete(struct dio *dio, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81375790)
Location: fs/direct-io.c:502
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:dio_bio_end_aio
```
**Symbols:**

```
ffffffff81375790-ffffffff81375822: dio_bio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
blk_status_t dio_bio_complete(struct dio *dio, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/direct-io.c (0)
Location: fs/direct-io.c:502
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:dio_bio_end_aio
```
**Symbols:**

```
ffffffff813c1e80-ffffffff813c1f2c: dio_bio_complete (STB_LOCAL)
ffffffff81cc4902-ffffffff81cc4917: dio_bio_complete.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
blk_status_t dio_bio_complete(struct dio *dio, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/direct-io.c (0)
Location: fs/direct-io.c:492
Inline: False
Direct callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:dio_bio_end_aio
```
**Symbols:**

```
ffffffff81448d00-ffffffff81448dfb: dio_bio_complete (STB_LOCAL)
ffffffff81e7730b-ffffffff81e77320: dio_bio_complete.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
blk_status_t dio_bio_complete(struct dio *dio, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/direct-io.c (0)
Location: fs/direct-io.c:492
Inline: False
Direct callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:dio_bio_end_aio
```
**Symbols:**

```
ffffffff814d7130-ffffffff814d7226: dio_bio_complete (STB_LOCAL)
ffffffff82069309-ffffffff8206931e: dio_bio_complete.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
blk_status_t dio_bio_complete(struct dio *dio, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/direct-io.c (0)
Location: fs/direct-io.c:498
Inline: False
Direct callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:dio_send_cur_page
  - fs/direct-io.c:dio_send_cur_page
  - fs/direct-io.c:dio_bio_end_aio
```
**Symbols:**

```
ffffffff81510160-ffffffff81510255: dio_bio_complete (STB_LOCAL)
ffffffff820e9396-ffffffff820e93ab: dio_bio_complete.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
blk_status_t dio_bio_complete(struct dio *dio, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/direct-io.c (0)
Location: fs/direct-io.c:498
Inline: False
Direct callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:dio_send_cur_page
  - fs/direct-io.c:dio_send_cur_page
  - fs/direct-io.c:dio_bio_end_aio
```
**Symbols:**

```
ffffffff81544610-ffffffff81544705: dio_bio_complete (STB_LOCAL)
ffffffff821c5f09-ffffffff821c5f1e: dio_bio_complete.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
blk_status_t dio_bio_complete(struct dio *dio, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffff8000103e3100)
Location: fs/direct-io.c:538
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:dio_bio_end_aio
```
**Symbols:**

```
ffff8000103e3100-ffff8000103e31b4: dio_bio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
blk_status_t dio_bio_complete(struct dio *dio, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (c05baff8)
Location: fs/direct-io.c:538
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:dio_bio_end_aio
```
**Symbols:**

```
c05baff8-c05bb0b4: dio_bio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
blk_status_t dio_bio_complete(struct dio *dio, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (c0000000004e8ec0)
Location: fs/direct-io.c:538
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:dio_bio_end_aio
```
**Symbols:**

```
c0000000004e8ec0-c0000000004e8fd8: dio_bio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
blk_status_t dio_bio_complete(struct dio *dio, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffe00029934c)
Location: fs/direct-io.c:538
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:dio_bio_end_aio
```
**Symbols:**

```
ffffffe00029934c-ffffffe0002993e2: dio_bio_complete (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
blk_status_t dio_bio_complete(struct dio *dio, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff813204d0)
Location: fs/direct-io.c:538
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:dio_bio_end_aio
```
**Symbols:**

```
ffffffff813204d0-ffffffff81320562: dio_bio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
blk_status_t dio_bio_complete(struct dio *dio, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81311070)
Location: fs/direct-io.c:538
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:dio_bio_end_aio
```
**Symbols:**

```
ffffffff81311070-ffffffff81311102: dio_bio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
blk_status_t dio_bio_complete(struct dio *dio, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff8131dfa0)
Location: fs/direct-io.c:538
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:dio_bio_end_aio
```
**Symbols:**

```
ffffffff8131dfa0-ffffffff8131e032: dio_bio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
blk_status_t dio_bio_complete(struct dio *dio, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff8132fca0)
Location: fs/direct-io.c:538
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:dio_bio_end_aio
```
**Symbols:**

```
ffffffff8132fca0-ffffffff8132fd32: dio_bio_complete (STB_LOCAL)
```
</details>
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>blk_status_t</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
